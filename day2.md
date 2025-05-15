# 🧭 Day 2: Time Complexity & Math Foundations

---

> 💡 **Reminder:** If you feel you haven't practiced your chosen programming language enough, feel free to revisit [Day 1](./day1.md) and solve more problems from the lists provided there before diving deep into today's topics.

---

## Time Complexity – Analyzing Algorithms

### Step 1: Understand Key Concepts

* **Big O, Ω, Θ** – formal definitions for upper, lower, and tight bounds.
* **Time vs. Space Complexity** – how runtime and memory grow with input size.

### 🎥 Tutorials (One-Shot Style)

* 🔗 **Time & Space Complexity Basics** (YouTube): [Watch here](https://youtu.be/FPu9Uld7W-E?si=OoljMO03zzKBCaDg)
* 🔗 **Time Complexity Simplified** (YouTube): [Watch here](https://youtu.be/BgLTDT03QtU?si=pDBp_gP-8CJX5sz1)
* 🔗 **Advanced Time Complexity & Recurrence Practice** (YouTube): [Watch here](https://youtu.be/mV3wrLBbuuE?si=B7hoH7QktEYJhaYq)
* 🔗 **Time & Space Complexity Overview** (GeeksforGeeks): [Read here](https://www.geeksforgeeks.org/time-complexity-and-space-complexity/)

### 🛠️ Step 2: Practice Analysis

- <input type="checkbox" id="day2_time_gfg"> Solve time-complexity practice problems on GFG  
  ▶️ [GFG Practice](https://www.geeksforgeeks.org/practice-questions-time-complexity-analysis/)

### Checklist

- <input type="checkbox" id="day2_time_tutorials"> Watched both YouTube tutorials  
- <input type="checkbox" id="day2_time_gfg_article"> Read the GeeksforGeeks article  
- <input type="checkbox" id="day2_time_gfg_practice"> Completed at least 5 GFG practice problems

---

## Math Foundations – Number Theory Basics

### 📖 Step 1: Grasp Core Topics

* **Divisibility & Primes**
* **GCD, LCM & Modular Arithmetic**
* **Basic Proof Techniques**

### 🎥 & 📚 Tutorials

* 🔗 **Intro to Number Theory** (YouTube): [Watch here](https://www.youtube.com/watch?v=1xNbjMdbjug)
* 🔗 **HackerEarth Tutorial**: [Read here](https://www.hackerearth.com/practice/math/number-theory/basic-number-theory-1/tutorial/)

### 🛠️ Step 2: Practice Problems

- <input type="checkbox" id="day2_math_hackerrank"> Solve "Number Groups" on HackerRank  
  ▶️ [HackerRank](https://www.hackerrank.com/challenges/number-groups/problem?isFullScreen=true)
- <input type="checkbox" id="day2_math_codeforces_ad"> Solve Codeforces Group problems A–D:

  * A: [Problem A](https://codeforces.com/group/MWSDmqGsZm/contest/223338/problem/A)  
  * B: [Problem B](https://codeforces.com/group/MWSDmqGsZm/contest/223338/problem/B)  
  * C: [Problem C](https://codeforces.com/group/MWSDmqGsZm/contest/223338/problem/C)  
  * D: [Problem D](https://codeforces.com/group/MWSDmqGsZm/contest/223338/problem/D)

### Checklist

- <input type="checkbox" id="day2_math_tutorials"> Watched YouTube intro & read HackerEarth  
- <input type="checkbox" id="day2_math_hackerrank_problem"> Completed HackerRank problem  
- <input type="checkbox" id="day2_math_codeforces_problems"> Solved all 4 Codeforces problems

---

## 🌟 Day 3+: More Practice & Deep Dives

* 🚀 **Complete Problem Sheet**: [Codeforces Full Set](https://codeforces.com/group/MWSDmqGsZm/contest/223338)
* 🧠 Tackle harder variants, compare different solutions, and optimize.

## 🔔 Need Help?

Join our **Discord Doubt Channel** anytime if you get stuck—we’re here to mentor you step-by-step!

[![Join us on Discord](https://img.icons8.com/color/48/discord-logo.png)](https://discord.gg/D3jDzyAE)

> contributed by [charanreddy-git](https://github.com/charanreddy-git/)

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
