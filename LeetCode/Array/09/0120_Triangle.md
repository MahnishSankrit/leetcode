# 120. Triangle

![LeetCode](https://img.shields.io/badge/LeetCode-%2523120-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 27, 2026 at 05:33 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/triangle/) |

## Solution

```unknown
class Solution {
public:
    int solve(vector<vector<int>> &triangle, int m, int n, int i,int j, vector<vector<int>> &
    dp){
        if(i == m-1) return triangle[i][j];

        if(dp[i][j] != INT_MAX) return dp[i][j];

        int left = triangle[i][j] + solve(triangle, m, n, i+1, j, dp);
        int right = triangle[i][j] + solve(triangle, m, n, i+1, j+1, dp);

        dp[i][j] = min(left, right);
        return dp[i][j];
    }
    int minimumTotal(vector<vector<int>>& triangle) {
        int m=triangle.size();

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-27*