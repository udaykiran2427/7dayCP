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

# 🧭 Day 4: Prefix Sum

## 📅 Reminder  
> 🚨 **AtCoder Contest today at 5:30 PM** [[**Beginner Contest 406**](https://atcoder.jp/contests/abc406)] - Don't miss it! Try to apply prefix sum knowledge if any relevant problems come up.

---

## 📖 Definition
**Prefix Sum** is an array where each element at index `i` contains the sum of elements from index `0` to `i` in the original array.  
It is a powerful technique to answer range queries in constant time after linear-time precomputation.

---

## 🚀 Why Use Prefix Sum?
- Speeds up repeated range sum calculations  
- Useful in subarray problems, matrix queries, and advanced optimizations  
- Reduces time complexity from O(n) per query to O(1)  

---

## 🎥 Tutorials
- <input type="checkbox" id="f"> 🔗 **Introduction & Definition** : [Watch here](https://www.youtube.com/watch?v=yuws7YK0Yng)  
- <input type="checkbox" id="g"> 🔗 **Implementation & Approaches** : [Read here](https://takeuforward.org/data-structure/prefix-sum-technique/)  
- <input type="checkbox" id="h"> 🔗 **Introduction & Problems (C++ & Python)** *(Optional)* : [Watch here](https://youtu.be/PhgtNY_-CiY?si=VmPhhwEYHh-L5GZU)  
- <input type="checkbox" id="i"> 🔗 **Implementation & Applications** *(Script)* : [Read here](https://www.geeksforgeeks.org/prefix-sum-array-implementation-applications-competitive-programming/)  

---

## 🔝 Top 5 Topics & Practice Questions (Easy & Medium)

### 1. ✅ Range Sum Queries

| Difficulty | Problem | Platform | Link |
|------------|---------|----------|------|
| Easy       | Range Sum Query | GFG | [🔗 Link](https://www.geeksforgeeks.org/problems/range-sum-queries2353/0) |
| Easy       | Range Sum Query - Immutable | LeetCode | [🔗 Link](https://leetcode.com/problems/range-sum-query-immutable/) |
| Medium     | Range Sum | Codeforces | [🔗 Link](https://codeforces.com/problemset/problem/817/C) |

---

### 2. 🔄 Subarray with Given Sum

| Difficulty | Problem | Platform | Link |
|------------|---------|----------|------|
| Easy       | Subarray with Given Sum | GFG | [🔗 Link](https://practice.geeksforgeeks.org/problems/subarray-with-given-sum/0) |
| Medium     | Subarray Sum Equals K | LeetCode | [🔗 Link](https://leetcode.com/problems/subarray-sum-equals-k/) |

---

### 3. 🧮 2D Prefix Sum (Matrix)

| Difficulty | Problem | Platform | Link |
|------------|---------|----------|------|
| Easy       | Matrix Block Sum | LeetCode | [🔗 Link](https://leetcode.com/problems/matrix-block-sum/) |
| Medium     | Submatrix Sum Queries | GFG | [🔗 Link](https://www.geeksforgeeks.org/submatrix-sum-queries/) |

---

### 4. ➕ Even/Odd or Custom Range Sums

| Difficulty | Problem | Platform | Link |
|------------|---------|----------|------|
| Easy       | Sum of All Odd Length Subarrays | LeetCode | [🔗 Link](https://leetcode.com/problems/sum-of-all-odd-length-subarrays/) |
| Medium     | XOR Queries of a Subarray | LeetCode | [🔗 Link](https://leetcode.com/problems/xor-queries-of-a-subarray/) |

---

### 5. 🧠 Equilibrium / Balance Index Problems

| Difficulty | Problem | Platform | Link |
|------------|---------|----------|------|
| Easy       | Pivot Index | LeetCode | [🔗 Link](https://leetcode.com/problems/find-pivot-index/) |
| Medium     | Minimum Value to Get Positive Step by Step Sum | LeetCode | [🔗 Link](https://leetcode.com/problems/minimum-value-to-get-positive-step-by-step-sum/) |
| Medium     | Balance Array | Codeforces | [🔗 Link](https://codeforces.com/contest/1343/problem/C) |

---

## 📘 In-Depth Learning & Practice
- 🔗 [Prefix Sum Problems - LeetCode](https://leetcode.com/problem-list/prefix-sum/)  
- 🔗 [Prefix Practice - CodeChef](https://www.codechef.com/practice/prefix-sums)  

---

## ✅ Advantages of Using Prefix Sum
- Fast range queries with O(1) time after O(n) preprocessing  
- Simplifies complex problems by turning repeated sums into simple subtractions  
- Space-efficient, requiring only an extra array of the same size  
- Versatile and extendable to 2D arrays and other algorithms  
- Improves overall performance by reducing query time drastically  

---

## ✅ Checklist

- <input type="checkbox" id="a"> Understood the definition and concept of prefix sum  
- <input type="checkbox" id="b">Practiced problems across all 5 key topics (range sum, subarray, 2D, custom sum, balance index)  
- <input type="checkbox" id="c">Explored both video and article tutorials for prefix sum  
- <input type="checkbox" id="d">Learned at least 3 real-world applications of prefix sum  
- <input type="checkbox" id="e">Solved easy & medium-level problems on LeetCode, GFG, CodeChef, and Codeforces  

---

## 💡 Motivational Quote

> **"Precompute today, save time tomorrow — prefix sum is the smart coder’s shortcut to speed."**

---

## 🔔 Need Help?

Join our **Discord Doubt Channel** anytime if you get stuck — we’re here to mentor you step-by-step!

[![Join us on Discord](https://img.icons8.com/color/48/discord-logo.png)](https://discord.gg/D3jDzyAE)

> Contributed by [parthu-333](https://github.com/parthu-333)

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
