# 63. Unique Paths II

![LeetCode](https://img.shields.io/badge/LeetCode-%252363-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 25, 2026 at 05:29 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/unique-paths-ii/) |

## Solution

```unknown
    }
        return dp[i][j] = right + down;

        int down = solve(m, n, i, j+1, grid, dp);
        int right = solve(m, n, i+1, j, grid, dp);

        if(dp[i][j] != -1) return dp[i][j];

        if(grid[i][j] == 1) return 0;
        if(i >= m || j >= n) return 0;
    int solve(int m, int n, int i, int j, vector<vector<int>> &grid, vector<vector<int>> &dp){
        if(i == m-1 && j == n-1) return 1;
// only recursion will give you the tle
public: 
class Solution {
// this was the memo method 

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-25*