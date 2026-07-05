# 7. Reverse Integer

![LeetCode](https://img.shields.io/badge/LeetCode-%25237-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Math |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 5, 2026 at 04:59 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/reverse-integer/description/) |

## Solution

```unknown
class Solution {
public:
    int reverse(int x) {
        long long y=0;
        while(x != 0){
            int digit = x % 10;
            y = y * 10 + digit;
            x /= 10;
        }
        if(y > INT_MAX || y < INT_MIN) return 0;
        return y;
        
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-05*