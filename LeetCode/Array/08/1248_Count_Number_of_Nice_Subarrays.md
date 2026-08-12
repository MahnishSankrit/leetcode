# 1248. Count Number of Nice Subarrays

![LeetCode](https://img.shields.io/badge/LeetCode-%25231248-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Hash Table, Math, Sliding Window, Prefix Sum |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 12, 2026 at 11:44 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/count-number-of-nice-subarrays/submissions/2104612863/) |

## Solution

```unknown
               }
                odd--;
               if(nums[j] % 2 != 0){
               j++;
            }
            count += i - j +1 ;
        }

        return count;
    }
    int numberOfSubarrays(vector<int>& nums, int k) {
        int n=nums.size();
        int count = 0;


        return sub(nums, k) - sub(nums, k-1);
    }

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-12*