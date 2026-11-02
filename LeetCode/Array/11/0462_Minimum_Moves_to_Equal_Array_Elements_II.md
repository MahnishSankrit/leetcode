# 462. Minimum Moves to Equal Array Elements II

![LeetCode](https://img.shields.io/badge/LeetCode-%2523462-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Math, Sorting |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 3, 2026 at 02:06 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-moves-to-equal-array-elements-ii/submissions/2188096094/) |

## Solution

```unknown
        int sum = 0;

    
        sort(nums.begin(), nums.end());
        int median = nums[n/2];


        for(int i=0; i<n; i++){
            int val = abs(nums[i] - median);
            sum += val;
        }

        return sum;
        int maxi =  INT_MIN;
        int mini = INT_MAX;
        int n=nums.size();
    int minMoves2(vector<int>& nums) {

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-02*