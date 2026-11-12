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
| **Submitted** | November 13, 2026 at 04:00 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/longest-strictly-increasing-or-strictly-decreasing-subarray/submissions/2194934060/) |

## Solution

```unknown
        for(int i=0; i<n; i++){

        }
                else break;
            }
                count = max(count, len+1);
                if(nums[j] > nums[j-1]) len++;
            int len = 0;
            for(int j=i+1; j<n; j++){
                if(nums[j] < nums[j-1]) len++;
                else break;
            for(int j=i+1; j<n; j++){
            }
            count = max(count, len+1);
        }
        return count;
    }

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-12*