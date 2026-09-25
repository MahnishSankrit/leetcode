# 931. Minimum Falling Path Sum

![LeetCode](https://img.shields.io/badge/LeetCode-%2523931-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 25, 2026 at 06:14 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-falling-path-sum/submissions/2152975570/) |

## Solution

```unknown
    }
        return dp[i][j] = min(down, min(left, right));

        int  right = matrix[i][j] + solve(m, n, i+1, j+1, matrix, dp);
        int  down = matrix[i][j] + solve(m, n, i+1, j, matrix, dp);
        int left = matrix[i][j] + solve(m, n, i+1, j-1, matrix, dp);

        if(i == m-1) return dp[i][j] = matrix[i][j];
        if(dp[i][j] != -1000000) return dp[i][j]; // tjis is the memo method

    int solve(int m, int n, int i, int j, vector<vector<int>> &matrix, vector<vector<int>> &dp)
    {
        if(j < 0 || j >= n) return 1e9;
    int minFallingPathSum(vector<vector<int>>& matrix) {
        int m=matrix.size();
        int n=matrix[0].size();


```

---
*Auto-synced by LeetCode Git Sync on 2026-09-25*