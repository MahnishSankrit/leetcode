# 3942. Minimum Operations to Sort a Permutation

![LeetCode](https://img.shields.io/badge/LeetCode-%25233942-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 22, 2026 at 05:05 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-operations-to-sort-a-permutation/submissions/2178763777/) |

## Solution

```unknown
            return min(left, right);
        } 

        if(dsc == n-1){
            int left = n - nums.back() + 1;
            int right =  (nums[0] + 1) % n + 1;
            return min(left, right);
        }

        return -1; 
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-22*