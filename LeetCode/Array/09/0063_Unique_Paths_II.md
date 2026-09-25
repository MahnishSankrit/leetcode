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
| **Submitted** | September 25, 2026 at 05:41 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/unique-paths-ii/submissions/2152954047/) |

## Solution

```unknown
        vector<vector<int>> dp(m, vector<int>(n, 0));
        // vector<vector<int>> dp(m, vector<int>(n, -1));
        if(obstacleGrid[0][0] == 1) return 0;

        if(obstacleGrid[m-1][n-1] == 1) return 0;
        int m=obstacleGrid.size();
        int n=obstacleGrid[0].size();
    int uniquePathsWithObstacles(vector<vector<int>>& obstacleGrid) {
        return dp[i][j] = right + down;
    }

        int down = solve(m, n, i, j+1, grid, dp);
        int right = solve(m, n, i+1, j, grid, dp);

        if(dp[i][j] != -1) return dp[i][j];

        if(grid[i][j] == 1) return 0;

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-25*