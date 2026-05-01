| File                           | Problem                 | Approach                      | Pattern             | Time         | Space     |
| ------------------------------ | ----------------------- | ----------------------------- | ------------------- | ------------ | --------- |
| `dnc_merge_sort_recursion.cpp` | Merge Sort              | Divide → Sort → Merge         | Divide & Conquer    | O(n log n)   | O(n)      |
| `merge_two_sorted_array.cpp`   | Merge 2 Sorted Arrays   | Two pointers, pick smaller    | Two Pointers        | O(n + m)     | O(n)      |
| `lc_33_rotated_array.cpp`      | Search in Rotated Array | Binary search on sorted half  | Binary Search       | O(log n)     | O(1)      |
| `lc_724_pivot_idx.cpp`         | Pivot Index             | Left sum == right sum         | Prefix Sum          | O(n)         | O(1)      |
| `lc_120_triangle.cpp`          | Min Path Sum (Triangle) | Bottom-up DP                  | Dynamic Programming | O(n²)        | O(n)      |
| `lc_1981_min_abs_diff.cpp`     | Min Absolute Difference | Track all sums (DP / set)     | Dynamic Programming | ~O(m·target) | O(target) |
| `lc_322_coin_change.cpp`       | Coin Change             | dp[i] = min(dp[i - coin] + 1) | Knapsack (DP)       | O(n·amount)  | O(amount) |
| `rat_in_maze.cpp`              | Rat in a Maze           | Try paths + backtrack         | Backtracking        | Exponential  | O(n²)     |
