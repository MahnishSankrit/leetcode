# 3105. Longest Strictly Increasing or Strictly Decreasing Subarray

![LeetCode](https://img.shields.io/badge/LeetCode-%25233105-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 13, 2026 at 04:15 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/longest-strictly-increasing-or-strictly-decreasing-subarray/submissions/2194937614/) |

## Solution

```unknown
       len = 1;
       while(j < n){
        if(nums[j] < nums[j-1]){
            len = j - i +1;
        }else{
            i= j;
       j=1;
        i=0;

        }
            len = 1;
        }
        count = max(count, len);
        j++;
       }
        return count;
    }

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-12*