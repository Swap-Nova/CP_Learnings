## 📌 Solved Problems & Approaches

### 🔹 `dnc_merge_sort_recursion.cpp`

**Problem:** Merge Sort using recursion
**Approach:** Divide the array into halves recursively, then merge sorted halves.
**Pattern:** Divide & Conquer
**Key Idea:** Split → Sort → Merge

---

### 🔹 `merge_two_sorted_array.cpp`

**Problem:** Merge two sorted arrays
**Approach:** Use two pointers to compare elements and build a merged sorted array.
**Pattern:** Two Pointers
**Key Idea:** Increment pointer of smaller element

---

### 🔹 `lc_33_rotated_array.cpp`

**Problem:** Search in Rotated Sorted Array
**Approach:** Modified Binary Search by identifying sorted half in each step.
**Pattern:** Binary Search Variant
**Key Idea:** One half is always sorted

---

### 🔹 `lc_724_pivot_idx.cpp`

**Problem:** Find Pivot Index
**Approach:** Compute total sum, then iterate while maintaining left sum.
**Pattern:** Prefix Sum
**Key Idea:** Left sum == Right sum

---

### 🔹 `lc_120_triangle.cpp`

**Problem:** Minimum Path Sum in Triangle
**Approach:** Bottom-up DP to accumulate minimum path values.
**Pattern:** Dynamic Programming
**Key Idea:** Build solution from last row upwards

---

### 🔹 `lc_1981_min_abs_diff.cpp`

**Problem:** Minimize Difference Between Target and Chosen Elements
**Approach:** Use DP with set/bitset to track possible sums.
**Pattern:** DP + State Space Optimization
**Key Idea:** Track all reachable sums row by row

---

### 🔹 `lc_322_coin_change.cpp`

**Problem:** Coin Change
**Approach:** Bottom-up DP to find minimum coins for each amount.
**Pattern:** Unbounded Knapsack (DP)
**Key Idea:** dp[i] = min(dp[i - coin] + 1)

---

### 🔹 `rat_in_maze.cpp`

**Problem:** Rat in a Maze
**Approach:** Backtracking to explore all valid paths.
**Pattern:** Recursion + Backtracking
**Key Idea:** Try all directions, mark visited, backtrack

---

## 🚀 Summary

* **Divide & Conquer:** Merge Sort
* **Binary Search:** Rotated Array
* **Dynamic Programming:** Triangle, Coin Change, Min Abs Diff
* **Backtracking:** Rat in Maze
* **Prefix Sum / Two Pointers:** Pivot Index, Merge Arrays

---
