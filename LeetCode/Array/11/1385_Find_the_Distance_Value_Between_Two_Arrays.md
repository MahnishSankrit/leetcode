# 1385. Find the Distance Value Between Two Arrays

![LeetCode](https://img.shields.io/badge/LeetCode-%25231385-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Two Pointers, Binary Search, Sorting |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 6, 2026 at 12:21 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/find-the-distance-value-between-two-arrays/submissions/2190305096/) |

## Solution

```unknown
            int val2 = arr1[i] + d;

            int res1 = lowerBound(arr2, val1);
            // int res2 = upperBound(arr2, val2);
            if(res1 == -1 || arr2[res1] > val2 ) count++;
             
            // if(res1 <= res2) count++;
        }

        return count;  
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-05*