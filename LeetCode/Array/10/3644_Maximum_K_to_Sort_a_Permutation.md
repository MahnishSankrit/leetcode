# 3644. Maximum K to Sort a Permutation

![LeetCode](https://img.shields.io/badge/LeetCode-%25233644-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Bit Manipulation |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 23, 2026 at 07:04 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/maximum-k-to-sort-a-permutation/submissions/2179261959/) |

## Solution

```unknown
        if(isSorted(nums)) return 0;

        // if(nums[0] != 0) return 0;
        int k=-1;

        for(int i=0; i<nums.size(); i++){
            if(nums[i] != i){
                // k = k & nums[i];
            }
        }
    int sortPermutation(vector<int>& nums) {
    }
                if(k == -1){
                    k=nums[i];
                }else{
                    k &= nums[i];
                }

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-23*