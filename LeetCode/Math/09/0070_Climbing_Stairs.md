# 70. Climbing Stairs

![LeetCode](https://img.shields.io/badge/LeetCode-%252370-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Math, Dynamic Programming, Memoization |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 20, 2026 at 11:35 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/climbing-stairs/) |

## Solution

```unknown
        if(n <= 1) return 1;

        if(dp[n] != -1) return dp[n];
        int take = climb(n-1, dp);
        int notTake = climb(n-2, dp);
        dp[n] = take + notTake;

        return take + notTake;

    }

    int climbStairs(int n) {
        vector<int> dp(n+1, -1);
       return climb(n, dp);
        
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-20*