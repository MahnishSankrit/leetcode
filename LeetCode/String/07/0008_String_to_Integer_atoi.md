# 8. String to Integer (atoi)

![LeetCode](https://img.shields.io/badge/LeetCode-%25238-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 24, 2026 at 04:47 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/string-to-integer-atoi/submissions/2079497138/) |

## Solution

```unknown
            // Overflow check
            if (!neg && num > INT_MAX)
                return INT_MAX;

            if (neg && -num < INT_MIN)
                return INT_MIN;

            i++;
        }

        if (neg)
            return -num;

        return num;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-24*