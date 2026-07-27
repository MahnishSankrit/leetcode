# 39. Combination Sum

![LeetCode](https://img.shields.io/badge/LeetCode-%252339-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Backtracking |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 27, 2026 at 11:35 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/combination-sum/submissions/2083794337/) |

## Solution

```unknown
        }
        
            comb(ans, arr,nums, k, i, sum+nums[i]);
            arr.push_back(nums[i]);
        if(sum < k) {

        if( i == nums.size()) return;
        // sum = sum-nums[i];
        if(!arr.empty()){
            arr.pop_back();
        }
        comb(ans, arr, nums, k, i+1, sum);
        // comb(ans, arr, nums, k, i+1, sum);
    }

    vector<vector<int>> combinationSum(vector<int>& candidates, int target) {
        vector<vector<int>> ans;

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-27*