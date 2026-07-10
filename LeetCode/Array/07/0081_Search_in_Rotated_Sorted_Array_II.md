# 81. Search in Rotated Sorted Array II

![LeetCode](https://img.shields.io/badge/LeetCode-%252381-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Binary Search |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 10, 2026 at 08:51 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/submissions/2063000844/) |

## Solution

```unknown
                    high=mid - 1;
                }else {
                    low = mid + 1;
                }
            }else {
                if(nums[high] >= target && target >= nums[mid]){
                    low = mid + 1;
                }else {
                    high = mid - 1;
                }
            }
        }
        return false;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-10*