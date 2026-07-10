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
| **Submitted** | July 10, 2026 at 07:49 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/search-in-rotated-sorted-array/description/) |

## Solution

```unknown

       if(n == 1) return nums[0] == target ? 0 : -1;

        int n=nums.size();
        int idx = 0;
    int search(vector<int>& nums, int target) {
    }
        return -1;
        }
            }
                low = mid + 1;
            }else{
                high = mid -1;
            }else if(nums[mid] > target){
                return mid;
            if(nums[mid] == target){

            int mid = low + (high - low)/2;
        while(low <= high){
    int binary(vector<int>& nums, int low , int high,int  target){

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-10*