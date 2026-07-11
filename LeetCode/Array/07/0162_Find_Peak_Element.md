# 162. Find Peak Element

![LeetCode](https://img.shields.io/badge/LeetCode-%2523162-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Binary Search |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 11, 2026 at 08:08 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/find-peak-element/submissions/2063965682/) |

## Solution

```unknown
           long long  left = (mid == 0) ? LLONG_MIN : nums[mid - 1];
            long long  right = (mid == n - 1) ? LLONG_MIN : nums[mid + 1];

            if(nums[mid] > left && nums[mid]>right){
                return mid;
            }else if(nums[mid] < left){
                high = mid -1;
        while(low <= high){
            int mid = low + (high - low)/2;

        // nums[n] = INT_MIN;
            }else {
                low = mid + 1;
            }

        }
        // nums[-1] =  INT_MIN;
        int high = n-1;
        int low = 0;


```

---
*Auto-synced by LeetCode Git Sync on 2026-07-11*