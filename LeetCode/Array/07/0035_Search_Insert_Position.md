# 35. Search Insert Position

![LeetCode](https://img.shields.io/badge/LeetCode-%252335-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Binary Search |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 9, 2026 at 01:44 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/search-insert-position/submissions/2061006178/) |

## Solution

```unknown

            if(nums[mid] == target){
                return mid;
            }else if(nums[mid] > target){
                high = mid- 1;
            }else{
                low = mid + 1;
            }
            int mid = low + (high - low)/2;
       while(low <= high){

        int idx = 0;
        int high = n-1;
        int low = 0;

        int n=nums.size();
    int searchInsert(vector<int>& nums, int target) {
public:
class Solution {

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-08*