# 153. Find Minimum in Rotated Sorted Array

![LeetCode](https://img.shields.io/badge/LeetCode-%2523153-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Binary Search |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 11, 2026 at 02:31 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) |

## Solution

```unknown
            mini = min(mini, nums[mid]);

            if(nums[low] < nums[mid]){
                if(nums[low] < nums[high]){
                    // high = mid - 1;
                    high--;
                }else{

            int mid = low + (high - low) /2;
        while(low <= high){

        int mini = INT_MAX;
        int high = n-1;
        int low = 0;

        int n=nums.size();
    int findMin(vector<int>& nums) {
public:
class Solution {

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-10*