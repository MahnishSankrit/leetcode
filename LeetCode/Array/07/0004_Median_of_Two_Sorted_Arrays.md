# 4. Median of Two Sorted Arrays

![LeetCode](https://img.shields.io/badge/LeetCode-%25234-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-red) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Hard |
| **Topics** | Array, Binary Search, Divide and Conquer |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 14, 2026 at 12:19 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/median-of-two-sorted-arrays/submissions/2066568395/) |

## Solution

```unknown
    sort(arr.begin(), arr.end());


    int total = arr.size();
    int m = total / 2;
    if(total % 2 == 1){
        return arr[m];

    }

    return (arr[m] + arr[m-1]) / 2.0;

            return ((double)arr[m] + (double)arr[m-1])/2.0;


    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-13*