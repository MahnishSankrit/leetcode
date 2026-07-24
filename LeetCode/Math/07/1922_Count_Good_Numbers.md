# 1922. Count Good Numbers

![LeetCode](https://img.shields.io/badge/LeetCode-%25231922-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Math, Recursion |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 24, 2026 at 07:34 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/count-good-numbers/submissions/2079651953/) |

## Solution

```unknown
        // if(n == 1) return 5;

        long long eve = (n + 1)/2;
        long long odd = n - eve;

        long long  cal1= binPow(5, eve);
        long long  cal2 = binPow(4, odd) ;

        long long res = (cal1 * cal2) % MOD;   
        return (int)res;   
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-24*