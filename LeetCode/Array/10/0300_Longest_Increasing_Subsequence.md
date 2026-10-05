# 300. Longest Increasing Subsequence

![LeetCode](https://img.shields.io/badge/LeetCode-%2523300-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Binary Search, Dynamic Programming, Longest Increasing Subsequence |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 6, 2026 at 12:43 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/longest-increasing-subsequence/submissions/2163537424/) |

## Solution

```unknown
        int notTake = solve(nums, dp, i+1, j, n);

        return dp[i][j+1] = max(take, notTake); // doing the j+1 as we know j can be -1 which 
        is not possible so to be in the save guard we can do this that why i have done this 
    }

    int lengthOfLIS(vector<int>& nums) {
      int n=nums.size();
      vector<int> arr;
       
    //    return solve(nums, arr, 0, n);  // this one is the recursion + backtraing
    vector<vector<int>> dp(n + 1, vector<int> (n+1, -1));
    //  return solve(nums, arr, 0, -1, n); // thisi s for the recursion

    return solve(nums, dp, 0, -1, n); // this is for the memo method
 

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-05*