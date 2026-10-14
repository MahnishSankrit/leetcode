# 368. Largest Divisible Subset

![LeetCode](https://img.shields.io/badge/LeetCode-%2523368-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Math, Dynamic Programming, Sorting |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 15, 2026 at 12:49 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/largest-divisible-subset/submissions/2172472765/) |

## Solution

```unknown

        vector<vector<int>> dp(n+1, vector<int>(n+1, -1));
        
        // solve(nums, arr,temp, n, 0, -1);  // recursion + backtraking 
        // return arr;
        
        solveMemo(nums, dp, n, 0, -1);

        vector<int> ans;
        int prev = -1;
        for(int i=0; i<n; i++){
            int notTake = dp[i+1][prev+1];
            int take = 0;
            if(prev == -1 || nums[i] % nums[prev] == 0){
                take = 1+ dp[i+1][i+1];
            }

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-14*