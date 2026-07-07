# 67. Add Binary

![LeetCode](https://img.shields.io/badge/LeetCode-%252367-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Math, String, Bit Manipulation, Simulation |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 7, 2026 at 02:23 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/add-binary/) |

## Solution

```unknown
            }

            if (j >= 0) {
                sum += b[j] - '0';
                j--;
            }

            result += (sum % 2) + '0';
            carry = sum / 2;
        }

        reverse(result.begin(), result.end());
        return result;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-07*