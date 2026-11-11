# 3789. Minimum Cost to Acquire Required Items

![LeetCode](https://img.shields.io/badge/LeetCode-%25233789-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Math, Greedy |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 11, 2026 at 11:15 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-cost-to-acquire-required-items/submissions/2194079025/) |

## Solution

```unknown
        val1 = 1LL * cost1 * costBoth;
        val2 = 1LL * cost2 * costBoth;
        long long common = min(need1, need2);
        long long res = common * costBoth + (need1 - common) * cost1 + (need2 - common) * cost2;

        mini = min(mini, val1 + val2);

        // CASE 1 WHEN BOTH TYPES ARE CALCULATING

        long long val2 = 1LL * cost2 * need2;
        // CASE 2 WHEN ONLY THE THIRD TYPE IS TAKING  for both the type 1 and 2
        mini = min(mini, res);
        //case 3 when type is taking 
        mini = min(mini, 1LL * max(need1, need2) * costBoth);

        return mini;

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-11*