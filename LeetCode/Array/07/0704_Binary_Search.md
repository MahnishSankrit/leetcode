# 704. Binary Search

![LeetCode](https://img.shields.io/badge/LeetCode-%2523704-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Binary Search |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 9, 2026 at 01:34 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/binary-search/submissions/2061001087/) |

## Solution

```unknown
    int search(vector<int>& nums, int target) {
        
        int n=nums.size();
        int low = 0;
        int high = n-1;

        while(low <= high){
            int mid = low + (high - low)/2;
        }

            if(nums[mid] == target){
                return mid;
            }else if(nums[mid] > target){
                high = mid- 1;
            }else{
                low = mid + 1;
            }
    }
        return -1;
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-08*