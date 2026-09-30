# 416. Partition Equal Subset Sum

![LeetCode](https://img.shields.io/badge/LeetCode-%2523416-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming, Knapsack Problem, 0-1 Knapsack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 30, 2026 at 11:35 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/partition-equal-subset-sum/submissions/2158476631/) |

## Solution

```unknown
                if(nums[i] + j <= target/2){
                    take = dp[i+1][j+nums[i]];
                }

                bool  notTake = dp[i+1][j];
                bool take = false;
            for(int j=0; j<=target/2; j++){
        for(int i=n-1; i>=0; i--){

        dp[n][target/2] = 1;
        vector<vector<int>> dp(n+1, vector<int>(target/2+1, 0));
        // vector<vector<int>> dp(n, vector<int>(target/2, 0));
        if(target % 2 != 0) return false;
        }
            target += nums[i];
        for(int i=0; i<n; i++){
        int target = 0;

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-30*