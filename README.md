# 🐍 Python Practice Lab: Core Data Structures & Algorithmic Exercises

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/islamyasser424-design/Python-Task--03/blob/main/Python_Task_03.ipynb)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Data Structures](https://img.shields.io/badge/Data_Structures-Lists%20%7C%20Tuples%20%7C%20Sets%20%7C%20Dicts-8b5cf6?style=for-the-badge)]()
[![Portfolio](https://img.shields.io/badge/Portfolio-Online-06b6d4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://islamyasser424-design.github.io/portfolio-/)

> **A structured practical lab mastering foundational Python data structures—Lists, Tuples, Sets, and Dictionaries—featuring iterative data manipulation, mathematical set operations, and structured problem-solving workflows.**

---

## 📌 Table of Contents
- [📖 Overview & Objectives](#-overview--objectives)
- [🧩 Problem Breakdown & Solutions](#-problem-breakdown--solutions)
- [💡 Key Concepts & Takeaways](#-key-concepts--takeaways)
- [🚀 How to Run Locally & on Colab](#-how-to-run-locally--on-colab)
- [👤 Author & Connect](#-author--connect)

---

## 📖 Overview & Objectives

Efficient data analytics requires strong mastery of in-memory data structures. This notebook implements solutions for practical scenarios covering:
* **Sequences & Indexing:** Ordered data manipulation using **Lists** and **Tuples**.
* **Hash Collections:** Rapid lookups and unique element enforcement using **Sets** and **Dictionaries**.
* **Mathematical Set Theory:** Practical implementations of Set Union (`|`), Intersection (`&`), and Difference (`-`).
* **Control Flow & Accumulation:** Iterative aggregation, sentinel checks, and formatted output generation.

---

## 🧩 Problem Breakdown & Solutions

| Question | Topic / Concept | Scenario Description | Core Techniques |
| :---: | :--- | :--- | :--- |
| **Q1** | **List Iteration & Summation** | Iterating through an integer collection to compute aggregated totals based on conditional criteria. | `for` loops, numeric accumulators, conditionals |
| **Q2** | **Dictionary Key-Value Lookup** | Storing student score pairs, querying specific keys, and managing tabular grade records. | Dictionary key indexing, key-value access, `in` checks |
| **Q3** | **Tuple Immutability & Slicing** | Working with fixed-length immutable sequences, element extraction, and sequence slicing. | Tuple indexing, slicing `[start:stop]`, immutable types |
| **Q4** | **Set Deduplication** | Eliminating duplicate string records from noisy customer or student input lists. | `set()` constructor, hash uniqueness, duplicate removal |
| **Q5** | **Dictionary Catalog & Pricing** | Modeling an e-commerce product price catalog, looking up inventory prices, and calculating totals. | Key lookup, price accumulation, formatted string printing |
| **Q6** | **Iterative Loop Generation** | Accepting user integer inputs and generating structured multiplication tables from 1 to 10. | `input()`, `int()` casting, `range(1, 11)`, formatted output |
| **Q7** | **Set Theory Operations** | Comparing multi-discipline cohorts (Python vs SQL students) to find shared learners and unique participants. | Set Intersection (`&`), Set Union (`|`), Set Difference |

---

## 💡 Key Concepts & Takeaways

### 1. Set Operations for Cohort Analysis (Q7)
```python
# Comparing student cohorts across technology tracks
python_students = {"Ahmed", "Sara", "Ali", "Mona"}
sql_students    = {"Sara", "Omar", "Mona", "Youssef"}

# Both courses (Intersection)
both_courses = python_students.intersection(sql_students)
# Output: {'Mona', 'Sara'}

# All unique participants (Union)
all_students = python_students.union(sql_students)
# Output: {'Ahmed', 'Ali', 'Mona', 'Omar', 'Sara', 'Youssef'}
```

### 2. Time Complexity & Lookup Optimization
* **Lists / Tuples:** $O(n)$ search time complexity—suitable for ordered sequences.
* **Sets / Dictionaries:** $O(1)$ average search time complexity—essential for high-volume deduplication and dictionary lookups.

---

## 🚀 How to Run Locally & on Colab

### Run Online (Zero Setup):
Click the badge below to execute the notebook instantly in your browser via Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/islamyasser424-design/Python-Task--03/blob/main/Python_Task_03.ipynb)

### Run Locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/islamyasser424-design/Python-Task--03.git
   cd Python-Task--03
   ```
2. Launch Jupyter Notebook or VS Code:
   ```bash
   jupyter notebook Python_Task_03.ipynb
   ```

---

## 👤 Author & Connect

* **Islam Yasser** — Data Analyst & Business Intelligence
* 🌐 **Portfolio:** [islamyasser424-design.github.io/portfolio-](https://islamyasser424-design.github.io/portfolio-/)
* 💼 **LinkedIn:** [linkedin.com/in/islam-yasser-55048b378](https://www.linkedin.com/in/islam-yasser-55048b378/)
* 📧 **Email:** [islamyasser424@gmail.com](mailto:islamyasser424@gmail.com)
* 🐙 **GitHub:** [@islamyasser424-design](https://github.com/islamyasser424-design)
