# 746. Min Cost Climbing Stairs

![LeetCode](https://img.shields.io/badge/LeetCode-%2523746-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Dynamic Programming |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 23, 2026 at 12:02 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/min-cost-climbing-stairs/submissions/2150125478/) |

## Solution

```unknown
    }
    int minCostClimbingStairs(vector<int>& cost) {

        int skip = solve(cost, dp, n - 2) + cost[n];

        dp[n] = min(take, skip);
        return dp[n];
        int take = solve(cost, dp, n-1) + cost[n];

        if(dp[n] != -1) return dp[n];

        if(n == 0) return cost[0];
    int solve(vector<int> &cost, vector<int> &dp, int n){
public:
class Solution {
        if(n == 1) return cost[1];

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-22*