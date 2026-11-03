# 3736. Minimum Moves to Equal Array Elements III

![LeetCode](https://img.shields.io/badge/LeetCode-%25233736-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Math |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 3, 2026 at 08:12 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-moves-to-equal-array-elements-iii/submissions/2188667827/) |

## Solution

```unknown
            mini = max(nums[i], mini);
        }

        long long sum = 0;
        for(int i=0; i<n; i++){
            long long val = mini - nums[i];
        }
            sum += val;

        return (int)sum;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-03*