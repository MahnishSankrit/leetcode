# 198. House Robber

![LeetCode](https://img.shields.io/badge/LeetCode-%2523198-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 21, 2026 at 10:33 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/house-robber/) |

## Solution

```unknown
        
        int left  = nums[n] + find(nums, dp, n-2);
        int right = find(nums, dp, n-1);

       return dp[n] = max(left , right);
       
    }
    int rob(vector<int>& nums) {
        int n=nums.size();
        vector<int>dp(n+1, -1);

        return find(nums, dp, n-1);
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-21*