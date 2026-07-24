# 50. Pow(x, n)

![LeetCode](https://img.shields.io/badge/LeetCode-%252350-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Math, Recursion |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 24, 2026 at 07:05 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/powx-n/submissions/2079621216/) |

## Solution

```unknown
    }
    // double inverse(double x, int  n){
    //      return 1.0 / binPow(x, n);
    // }
        }
    double myPow(double x, int n) {
        if(n == 0) return 1;
        long long  num = n;
        
        if(num < 0) return (1.0/ binPow(x, -1 * num));
        return binPow(x, num);
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-24*