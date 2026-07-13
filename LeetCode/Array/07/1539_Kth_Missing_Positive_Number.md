# 1539. Kth Missing Positive Number

![LeetCode](https://img.shields.io/badge/LeetCode-%25231539-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Binary Search |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 13, 2026 at 11:44 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/kth-missing-positive-number/submissions/2066527431/) |

## Solution

```unknown

        while (low <= high) {
            int mid = low + (high - low) / 2;
            int missing = (arr[mid] - (mid + 1));

            if (missing >= k) {
                high = mid - 1;
            }
        int high = n - 1;
                low = mid + 1;
            } else {
        }
            return low+k;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-13*