# 3364. Minimum Positive Sum Subarray

![LeetCode](https://img.shields.io/badge/LeetCode-%25233364-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Sliding Window, Prefix Sum |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 14, 2026 at 11:35 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-positive-sum-subarray/submissions/2196113140/) |

## Solution

```unknown
        // int res2 = INT_MAX;
        // for(int i=0; i<n; i++){
        //     int sum = 0;
        //     for(int j=i; j<n; j++){
        //         sum += nums[j];
        //         if(sum > 0 && j - i + 1 == r){
        //             res1 = min(res1, sum);
        //         }
        //     }
        // } 
        if(res1 == INT_MAX) return -1;
        return res1;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-14*