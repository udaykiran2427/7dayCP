<style>
  input[type="checkbox"] {
    width: 18px;
    height: 18px;
    cursor: pointer;
    transition: box-shadow 0.3s ease, background-color 0.3s ease;
  }

  input[type="checkbox"]:hover {
    box-shadow: 0 0 5px 2px rgba(59, 130, 246, 0.6);
    background-color: rgba(59, 130, 246, 0.1);
  }

  input[type="checkbox"]:focus-visible {
    outline: 2px solid rgba(59, 130, 246, 0.8);
    outline-offset: 2px;
  }
</style>

# 🧭 Day 3: Binary Search

---

> 💡 **Reminder:** Binary Search applies to any monotonic or ordered solution space, not just sorted arrays. Mastering this mindset is key for contests and interviews.

---

Binary Search is an efficient algorithm to find elements or answers in a sorted or monotonic space with time complexity **O(log n)**.

---

## 🎥 Tutorials

- 🔗 **Binary Search Basics** – Clean explanation: [Watch here](https://youtu.be/MHf6awe89xw?si=9fzpri6SOdUyVObj)
- 🔗 **Advanced Binary Search Techniques** _(Optional)_ – [Watch here](https://youtu.be/GU7DpgHINWQ?si=iGWyuASZv7c7fFoJ)
- 🔗 **Python Implementation** – [Watch here](https://youtu.be/s4DPM8ct1pI?si=I30nABW4JuLj-DeZ)
- 🔗 **Java Implementation** – [Watch here](https://youtu.be/f6UU7V3szVw?si=Bt3dOrTuvCYHVWup&t=1761)

> ⚠️ Optional videos and problems can be done later for mastery.

---

# 📖 Key Binary Search Templates to Know

| Template Name     | Purpose                                     | When to Use                               |
| ----------------- | ------------------------------------------- | ----------------------------------------- |
| **Lower Bound**   | Find smallest index where condition is true | E.g., first element ≥ target              |
| **Upper Bound**   | Find largest index where condition is true  | E.g., last element ≤ target               |
| **Exact Match**   | Find exact target value in sorted array     | Basic binary search                       |
| **Search Answer** | Search space of answers, not array indices  | Optimization problems (min/max threshold) |

---

## 💡 Tips for Writing Binary Search Code

- Always define your search space clearly — low and high boundaries.
- Decide if your mid should be `mid = low + (high - low) // 2` to avoid overflow.
- Carefully handle boundary conditions to avoid infinite loops.
- Decide whether your loop condition is `while(low <= high)` or `while(low < high)` depending on the problem.
- Use helper functions to check the monotonic condition if complex.
- Dry run your code on corner cases: empty arrays, single element, all equal elements.

---

## 🎥 Keep Going! Recommended Playlist for After the Camp

- 🔗 [Striver's Binary Search Playlist](https://www.youtube.com/watch?v=_NT69eLpqks&list=PLgUwDviBIf0pMFMWuuvDNMAkoQFi-h0ZF)

---

## 📘 In-Depth Learning with Practice

- 🔗 **Codeforces EDU Binary Search Module**: [Start here](https://codeforces.com/edu/course/2/lesson/6)

---

## 🧪 Practice Problems – Sorted by Difficulty

### 🔹 Basics & Variants

- <input type="checkbox" id="bs_basic_1"> [LeetCode: Binary Search](https://leetcode.com/problems/binary-search/)
- <input type="checkbox" id="bs_basic_2"> [GFG: Floor in Sorted Array](https://www.geeksforgeeks.org/problems/floor-in-a-sorted-array-1587115620/1)
- <input type="checkbox" id="bs_basic_3"> [GFG: Ceil in Sorted Array](https://www.geeksforgeeks.org/problems/ceil-in-a-sorted-array/1)

---

### 🔸 Application & Technique-Based Binary Search Problems

| Difficulty  | Problem                        | Link                                                                                                                                                 |
| ----------- | ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Easy        | Search Insert Position         | <input type="checkbox" id="bs_var_1"> [LeetCode](https://leetcode.com/problems/search-insert-position/description/)                                  |
| Easy        | First and Last Occurrence      | <input type="checkbox" id="bs_var_2"> [LeetCode](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/description/) |
| Medium      | Sqrt(x)                        | <input type="checkbox" id="bs_var_3"> [LeetCode](https://leetcode.com/problems/sqrtx/description/)                                                   |
| Medium      | Valid Perfect Square           | <input type="checkbox" id="bs_var_4"> [LeetCode](https://leetcode.com/problems/valid-perfect-square/description/)                                    |
| Medium      | First Bad Version              | <input type="checkbox" id="bs_var_5"> [LeetCode](https://leetcode.com/problems/first-bad-version/description/)                                       |
| Medium      | Find Peak Element              | <input type="checkbox" id="bs_var_6"> [LeetCode](https://leetcode.com/problems/find-peak-element/description/)                                       |
| Medium-Hard | Search in Rotated Sorted Array | <input type="checkbox" id="bs_var_7"> [LeetCode](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)                          |

- <input type="checkbox" id="bs_do_3"> Solve at least 3 problems from this list, starting with easier ones

---

## ✅ Binary Search Checklist

- <input type="checkbox" id="bs_tutorial"> Watched the intro tutorial
- <input type="checkbox" id="bs_prob_group"> Solved basic 3 problems (Binary Search, Floor, Ceil)
- <input type="checkbox" id="bs_variant_group"> Solved 3+ variant/application problems
- <input type="checkbox" id="bs_adv_video"> (Optional) Watched advanced techniques video
- <input type="checkbox" id="bs_adv_prob"> (Optional) Solved 1–2 advanced technique problems
- <input type="checkbox" id="bs_codeforces"> (Optional) Tried Codeforces EDU Binary Search module

---

## 🔔 Need Help?

Join our **Discord Doubt Channel** anytime if you get stuck—we’re here to mentor you step-by-step!

[![Join us on Discord](https://img.icons8.com/color/48/discord-logo.png)](https://discord.gg/D3jDzyAE)

> contributed by [udaykiran2427](https://github.com/udaykiran2427)

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const checkboxes = document.querySelectorAll('input[type="checkbox"]');
    checkboxes.forEach((checkbox) => {
      const isChecked = localStorage.getItem(checkbox.id) === "true";
      checkbox.checked = isChecked;
    });
    checkboxes.forEach((checkbox) => {
      checkbox.addEventListener("change", function () {
        localStorage.setItem(checkbox.id, checkbox.checked);
      });
    });
  });
</script>
