# 1480. Running Sum of 1d Array

![LeetCode](https://img.shields.io/badge/LeetCode-%25231480-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Prefix Sum |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 23, 2026 at 09:22 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/running-sum-of-1d-array/submissions/2151068222/) |

## Solution

```unknown
class Solution {
public:
    vector<int> runningSum(vector<int>& nums) {
        int n=nums.size();
        vector<int> ans;
        int sum = 0;
        for(int i=0; i<n; i++){
            ans.push_back(sum);
        }
    }
            sum += nums[i];

        return ans;
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-23*