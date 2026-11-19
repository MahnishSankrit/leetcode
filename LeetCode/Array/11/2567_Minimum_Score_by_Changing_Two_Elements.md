# 2567. Minimum Score by Changing Two Elements

![LeetCode](https://img.shields.io/badge/LeetCode-%25232567-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Greedy, Sorting |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 19, 2026 at 11:56 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-score-by-changing-two-elements/submissions/2199551788/) |

## Solution

```unknown
public:
    int minimizeSum(vector<int>& nums) {
        int n=nums.size();


        sort(nums.begin(), nums.end());

class Solution {
     // case 1 make nums[0] = nums[1] and nums[n-1] = nums[n-2];
        int case1 = abs(nums[1] - nums[n-2]);
        //case 2 make nums[0] = nums[2] and nums[1]  = nums[2];
        int case2 = abs(nums[2] - nums[n-1]);
        // case 3 make nums[n-1]  =nums[n-3] and nums[n-2] = nums[n-3];
        int case3 =abs(nums[n-3] - nums[0]);

        return min(min(case1, case2) , case3);

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-19*