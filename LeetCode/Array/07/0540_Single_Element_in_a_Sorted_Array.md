# 540. Single Element in a Sorted Array

![LeetCode](https://img.shields.io/badge/LeetCode-%2523540-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Binary Search |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 11, 2026 at 07:53 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/single-element-in-a-sorted-array/submissions/2063952216/) |

## Solution

```unknown
                    high = mid - 1;
                }else{
                if(nums[mid] != nums[mid + 1]){
                    low = mid + 2;
                }
            }else {
                if(nums[mid] != nums[mid -1] ){
                    high = mid - 1; 
                }else{
                    low = mid + 1;
                }
            }
        }
        return nums[low];
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-11*