# 453. Minimum Moves to Equal Array Elements

![LeetCode](https://img.shields.io/badge/LeetCode-%2523453-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Math |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 3, 2026 at 01:52 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-moves-to-equal-array-elements/submissions/2188089476/) |

## Solution

```unknown
class Solution {
public:
    int minMoves(vector<int>& nums) {
        int n=nums.size();
        int mini = INT_MAX;
        for(int i=0; i<n; i++){
            mini = min(mini, nums[i]);
        }
        int sum = 0;
        for(int i=0; i<n; i++){
            int val = nums[i] - mini;
        }
    }
            sum += val;

        return sum;

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-02*