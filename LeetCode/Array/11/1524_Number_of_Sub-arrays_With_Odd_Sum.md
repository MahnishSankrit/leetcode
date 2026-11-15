# 1524. Number of Sub-arrays With Odd Sum

![LeetCode](https://img.shields.io/badge/LeetCode-%25231524-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Math, Dynamic Programming, Prefix Sum |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 16, 2026 at 12:33 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/number-of-sub-arrays-with-odd-sum/submissions/2196850360/) |

## Solution

```unknown
                even++;
                count += odd;
            }else{
                count += even;
                odd++;
            }
            i++;
        }

        return count % mod;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-15*