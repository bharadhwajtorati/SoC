# 🚀 Summer of Code 2026

---

## 📌 About This Repository

> **Project ID:** 6
> 
> This repository serves as my official midterm submission for **Competitive Programming** in **SoC 2026, IIT Bombay**.

---

## 🧠 What I Have Learnt Till Now

*I am documenting my weekly learning progress below:*

### 🔹 Week 1 (Ad-hoc Basics & Core Data Structures)
* **Introduction to Data & Structures:** Learned the fundamental difference between raw data and structured data, understanding how organized data allows us to design highly efficient algorithms (e.g., how a sorted array enables Binary Search).
* **Algorithm Analysis:**
  * Explored how to calculate the resource consumption (time and space complexities) of an algorithm in a machine-independent way.
  * Mastered evaluating algorithms based on **Best case**, **Worst case**, and **Average case** performance.
* **Asymptotic Notation:**
  * Gained a deep understanding of **Big-O Notation** $O(n)$ to define upper bounds and approximate the growth rate of algorithms.
  * Covered **Theta-Notation** ($\Theta(n)$) for defining tight bounds.
  * Familiarized myself with the core complexity classes: Constant $O(1)$, Logarithmic $O(\log n)$, Linear $O(n)$, Quadratic $O(n^2)$, Polynomial $O(n^k)$, and Exponential $O(2^n)$.
* **Core Data Structures (Stacks & Queues):**
  * **Stack:** Deeper dive into Last-In-First-Out (LIFO) behavior, including core operations (`push`, `pop`, `top`, `empty`, `size`) and standard applications like string reversal, balancing parentheses, and identifying palindromes.
  * **Queue:** Understood First-In-First-Out (FIFO) mechanics, its standard operations (`enqueue`, `dequeue`, `front`), and how to implement a functional queue using two utility stacks.

### 🔹 Week 2 (Greedy, Sorting & Number Theory)
* **Greedy Algorithms & Optimization:**
  * Mastered making locally optimal choices at each step to reach a global optimum using materials from *Classic Algorithms: Greedy*.
  * Evaluated key properties: **Greedy Choice Property** and **Optimal Substructure**.
  * Analyzed classic applications like the *Optimal Service Time Scheduling* problem and the *Making Change* problem.
* **Binary Search Variants & Bounds:**
  * Studied non-trivial applications using *Binary Search and Variants* including the *Egg Drop Problem* (using Exponential Search for unknown ranges) and maximum subarray sums using prefix sums.
  * Explored Information Theory bounds proving why $\log N$ comparisons are strictly necessary for searching and sorting.
* **Divide & Conquer Paradigms:**
  * Analyzed the recursive framework using the Master Theorem based on *Divide and Conquer Applications*.
  * Implemented **Merge Sort**, counting *Significant Inversions* $O(n \log n)$, the *Skyline Problem*, and fast integer/matrix *Exponentiation* via repeated squaring.
* **Fundamental Number Theory & Math:**
  * **Euclidean Algorithm:** Studied the logarithmic time complexity $O(\log \min(a, b))$ optimization for finding the Greatest Common Divisor (GCD) and Least Common Multiple (LCM), including the high-performance *Binary GCD* variant detailed on [CP-Algorithms: Euclidean Algorithm](https://cp-algorithms.com/algebra/euclid-algorithm.html).
  * **Sieve of Eratosthenes:** Learned how to efficiently compute all prime numbers in a segment $[1, n]$ in $O(n \log \log n)$ operations using the implementation strategies from [CP-Algorithms: Sieve of Eratosthenes](https://cp-algorithms.com/algebra/sieve-of-eratosthenes.html). Explored optimizations like sieving till the square root, odd-only sieving, and *Segmented Sieve* architectures for massive ranges.
  * **Binomial Coefficients:** Mastered analytical and recurrence relations (Pascal's Triangle) to calculate $\binom{n}{k}$ combinations. Covered advanced modular arithmetic variations—including large prime modulos, prime powers, and square-free composites using the Chinese Remainder Theorem—as outlined on [CP-Algorithms: Binomial Coefficients](https://cp-algorithms.com/combinatorics/binomial-coefficients.html).

### 🔹 Weeks 3 & 4 (Dynamic Programming Optimization)
* **Core Paradigms & Foundations:**
  * Studied how to transition from exponential-time complete search algorithms into highly efficient polynomial-time variants.
  * Mastered identifying the two critical ingredients for DP viability: **Optimal Substructures** (where subproblem solutions form part of the original problem's solution) and **Overlapping Subproblems** (revisited computational states).
* **Implementation Styles:**
  * **Top-Down (Memoization):** Mastered intelligent recursive backtracking by caching subproblem states inside a lookup array, reducing the theoretical search space from $20^{20}$ to an $O(kM)$ state graph traversal.
  * **Bottom-Up (Tabular Method):** Developed iterative multi-dimensional table-filling frameworks using specific loop sequencing (topological sorting of underlying DAG states).
  * **Space-Saving Optimization:** Implemented matrix row/column reduction tricks to sacrifice obsolete dimensions, dramatically shrinking state memory footprints (e.g., sliding window arrays of size 2 instead of N).
* **Classical DP Problem Frameworks:**
  * **Longest Increasing Subsequence (LIS):** Implemented the quadratic $O(n^2)$ state relation and learned the output-sensitive greedy update paradigm optimized via binary search to execute in $O(n \log k)$.
  * **Max 2D Sub-Matrix Sum:** Solved static Range Sum Query matrix operations using prefix tables and inclusion-exclusion geometric principles to drop complexity to $O(n^4)$ and $O(n^3)$.
  * **0-1 Knapsack (Subset Sum):** Developed state transitions utilizing index boundaries and residual weights (`id`, `remW`) in an $O(NS)$ pseudo-polynomial matrix.
  * **Coin Change Variants:** Designed systems to calculate the absolute minimum coin configurations for amount $V$, alongside combinatorial coin variants that calculate unique composition counts.
  * **Traveling Salesman Problem (TSP):** Explored NP-hard path minimization over a graph matrix optimized using small-set booleans, breaking the factorial boundary down to $O(N^2 \cdot 2^N)$ using **DP + Bitmasking** techniques.
* **Non-Classical Formulations:**
  * Explored multi-stage array split optimizations like *Cutting Sticks* matrix chaining $O(n^3)$ and mathematical combinatorics breakdowns matching Pascal's Binomial distribution patterns.
  * Explored reconstructing precise optimal routes and asset combinations via reverse-tracking matrix predecessor pathways from optimal final states.

---

## 📈 Summary

During the first 4 weeks of **SoC 2026**, I built a strong algorithmic foundation by moving from basic data structures to complex optimization methods. 

By matching theory (complexity bounds, Master Theorem, and number theory) with hands-on practice, I maintained a **100% completion rate, solving all 55 out of 55 assigned problems** in the competitive programming group. This covered everything from ad-hoc simulations and greedy choices to advanced multi-dimensional dynamic programming.

---

## 💻 My Progress & Submissions

To view my active submissions, practice problems, and contest progress, please join my Codeforces group:

👉 **[Join the Codeforces Group](https://codeforces.com/group/MNl5W7SXII/contests)**
