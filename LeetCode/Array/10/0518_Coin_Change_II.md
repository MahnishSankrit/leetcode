# 518. Coin Change II

![LeetCode](https://img.shields.io/badge/LeetCode-%2523518-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming, Knapsack Problem, Complete Knapsack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 3, 2026 at 03:16 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/coin-change-ii/submissions/2160575681/) |

## Solution

```unknown

        }
        long long notTake = solve(coins, a, i+1, n, dp);
            take = solve(coins, a - coins[i], i, n, dp);
        if(a >= coins[i]){

        long long take = 0;

        if(dp[i][a] != -1) return dp[i][a];

        if(a == 0) return 1;
        if(i == n) return 0;
        
class Solution {
public:
    int solve(vector<int> &coins, int a, int i, int n, vector<vector<int>> &dp){

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-02*