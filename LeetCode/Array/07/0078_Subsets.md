# 78. Subsets

![LeetCode](https://img.shields.io/badge/LeetCode-%252378-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Backtracking, Bit Manipulation |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 28, 2026 at 12:03 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/subsets/submissions/2083834404/) |

## Solution

```unknown
class Solution {
public:

    vector<vector<int>> subsets(vector<int>& nums) {
        vector<vector<int>> ans;

    void comb(vector<vector<int>> &ans, vector<int> &arr, vector<int> &nums, int i){
        if(i == nums.size()){
    }
            ans.push_back(arr);
        }
            return;
        arr.push_back(nums[i]);
        comb(ans, arr, nums, i+1);
        arr.pop_back();
        comb(ans, arr, nums, i+1);

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-27*