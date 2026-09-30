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
| **Submitted** | September 30, 2026 at 11:20 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/partition-equal-subset-sum/submissions/2158459490/) |

## Solution

```unknown

    bool canPartition(vector<int>& nums) {
        int n=nums.size();
        int target = 0;
        for(int i=0; i<n; i++){

        return solve(nums, target/2, 0, 0, dp);
    }
            target += nums[i];
        }
        if(target % 2 != 0) return false;
        vector<vector<int>> dp(n, vector<int>(target/2, -1));
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-30*