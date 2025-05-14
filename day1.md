# 🧭 Day 1: Setting the Foundation – Language, Tools, and Warm-up

---

## 🛠️ Step 1: Choose Your Language

Pick **one language** that you’ll use. Preferably:

- **C++** – For performance and STL
- **Java** – For strong typing and structure
- **Python** – For simplicity

👉 [Read this comparison to help decide](https://medium.com/@burninghell/cpp-vs-java-vs-python-258c087eff2d)

### 🎥 One-Shot Video Guides:

- 🔗 **C++ One Shot:** [Watch here](https://youtu.be/EAR7De6Goz4?si=BNBFKe9Y3kQXAvSx)
- 🔗 **Java One Shot:** [Watch here](https://youtu.be/TAtrPoaJ7gc?si=xU4B3A6jrvEU3vLK)  
  _Note: Java takes more time to learn. You can follow this channel for a gradual and thorough approach._
- 🔗 **Python One Shot:** [Watch here](https://youtu.be/0K_eZGS5NsU?si=hOGOY3Z9XNE7cQMG)

---

## ⚙️ Step 2: Create Your Accounts

Create your accounts on these competitive programming platforms:

- [ ] [Codeforces](https://codeforces.com/)
- [ ] [LeetCode](https://leetcode.com/)
- [ ] [CodeChef](https://www.codechef.com/)
- [ ] [HackerRank](https://www.hackerrank.com/)

> 👉 **Tag the college** wherever possible (e.g., Codeforces, HackerRank).

---

## 💻 Step 3: Set Up Your Environment

Choose a local IDE or use an online judge.

### 🧰 IDE Suggestions

> For quick setups, you can use [CodeChef’s Online IDE](https://www.codechef.com/ide).  
> For full control, install a local IDE + compiler.

| Language | Recommended IDEs            | Compiler Needed |
| -------- | --------------------------- | --------------- |
| C++      | VSCode, Code::Blocks, CLion | MinGW/GCC       |
| Java     | IntelliJ, Eclipse           | JDK             |
| Python   | VSCode, PyCharm             | Python 3.x      |

---

## 📚 Step 4: Learn Language + Tools

- [ ] Watch your language's one-shot tutorial.
- [ ] Learn your language’s built-in data structures:

### STL / Collections / Built-ins

- **C++**: `vector`, `map`, `set`  
  🔗 [STL Guide](https://youtu.be/RRVYpIET_RU?si=FfmXf1AI0ASmMbG-)
- **Java**: `ArrayList`, `HashMap`, `TreeSet`  
  🔗 [Collections in Hindi](https://youtu.be/rzA7UJ-hQn4?si=FVVrVluu7HxMyj35)
- **Python**: `list`, `dict`, `set`  
  _(Covered in the one-shot video above)_

> 🧠 Tip: You can always learn them as you solve problems. Feel free to ask ChatGPT or any LLM if you're stuck.

---

## 🧪 Step 5: Practice Time!

Practice the basics of your chosen language (STL/collections included):

### 🔗 HackerRank Language Domains:

- [C++](https://www.hackerrank.com/domains/cpp)
- [Java](https://www.hackerrank.com/domains/java)
- [Python](https://www.hackerrank.com/domains/python)

### 🔗 Algorithm Practice:

- [HackerRank Basic Algorithms](https://www.hackerrank.com/domains/algorithms?filters%5Bdifficulty%5D%5B%5D=easy&filters%5Bskills%5D%5B%5D=Problem%20Solving%20%28Basic%29&badge_type=problem-solving)
- [Codeforces 800-rated Problems](https://codeforces.com/problemset?order=BY_SOLVED_DESC&tags=800-800)
- [CodeChef Beginner Problems](https://www.codechef.com/practice/basic-programming-concepts)

> 💡 **Pro Tip:** On Codeforces, sort by "Most Solved" and filter by 800-rated problems.

---

## 🏁 Step 6: Upcoming Contests — Register Now!

> _Participating in contests is **non-negotiable**. What matters is that you show up and try your best._

> ⚠️ **Important Ethics Notice:**  
> DO NOT use ChatGPT, GitHub Copilot, or any AI-based assistants during contests.  
> Participating honestly is the only way to truly improve. Cheating ruins your learning journey and disrespects the spirit of competitive programming. You owe it to yourself to try, fail, and grow.

### 🎯 Contest Schedule:

| Platform   | Contest Name             | Time & Date                | Duration      |
| ---------- | ------------------------ | -------------------------- | ------------- |
| CodeChef   | **Starters 186**         | Wed, 14 May 2025 – 8:00 PM | 2 hours       |
| Codeforces | **CF Round (Div. 2)**    | Sat, 17 May 2025 – 8:05 PM | 2 hours       |
| AtCoder    | **Beginner Contest 406** | Sat, 17 May 2025 – 5:30 PM | 1 hour 40 min |
| LeetCode   | **Weekly Contest 450**   | Sun, 18 May 2025 – 8:00 AM | 1.5 hours     |

> ✅ **Mandatory:** Participate in **CodeChef Starters 186**  
> 🔥 **Highly Recommended:** Register for all other contests too.

---

## 📌 Day 1 Task Checklist

- [ ] Chose a programming language and watched its one-shot video
- [ ] Learned syntax and STL / collections
- [ ] Set up an IDE or online judge
- [ ] Created accounts on Codeforces, LeetCode, CodeChef, HackerRank
- [ ] Tagged your college wherever possible
- [ ] Solved beginner-level problems
- [ ] Participated in **CodeChef Starters 186**
- [ ] Registered for all upcoming contests

---
<script>
document.addEventListener("DOMContentLoaded", () => {
  const checkboxes = document.querySelectorAll("input[type=checkbox]");
  checkboxes.forEach((checkbox, index) => {
    const id = "checkbox_" + index;

    // Load state
    const saved = localStorage.getItem(id);
    if (saved !== null) checkbox.checked = saved === "true";

    // Save state on change
    checkbox.addEventListener("change", () => {
      localStorage.setItem(id, checkbox.checked);
    });
  });
});
</script>