# 3871. Count Commas in Range II

![LeetCode](https://img.shields.io/badge/LeetCode-%25233871-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Math |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 9, 2026 at 10:25 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/count-commas-in-range-ii/) |

## Solution

```unknown
        if( n< 1000) return 0;
        if(n >= 1000){
            count += n-999;
        }
        if(n >= 1000000){
            count += n-999999;
        }
        if(n >= 1000000000){
            count+=n-999999999;
        }
        if (n >= 1000000000000LL) {
            count += n - 999999999999LL;
        }

        if (n >= 1000000000000000LL) {
            count += n - 999999999999999LL;

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-09*