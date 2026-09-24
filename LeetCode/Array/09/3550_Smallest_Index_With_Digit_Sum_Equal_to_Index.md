# 3550. Smallest Index With Digit Sum Equal to Index

![LeetCode](https://img.shields.io/badge/LeetCode-%25233550-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Math |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 24, 2026 at 07:53 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/smallest-index-with-digit-sum-equal-to-index/submissions/2152067971/) |

## Solution

```unknown
    }
    int smallestIndex(vector<int>& nums) {
        int n=nums.size();
        return val;

        for(int i=0; i<n; i++){
            if(digitsum(nums[i]) == i){
                return i;
            }
        }

        return -1;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-24*