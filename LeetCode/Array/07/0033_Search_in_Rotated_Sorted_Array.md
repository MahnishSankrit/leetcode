# 33. Search in Rotated Sorted Array

![LeetCode](https://img.shields.io/badge/LeetCode-%252333-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Binary Search |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 10, 2026 at 08:28 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/search-in-rotated-sorted-array/submissions/2062978756/) |

## Solution

```unknown
                high = mid - 1;
            if(nums[low] <= target && nums[mid] > target){
        if(nums[low] <= nums[mid]){ // it means that my left part is sorted

        }
            return mid;
        if(nums[mid] == target){
            }else{
                low = mid + 1;
            }
        }else{ // it means that the right part is sorted
            if(nums[high] >= target && nums[mid]  < target){
                low = mid + 1;

            }

        }
                high = mid - 1;
            }else{
       } 

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-10*