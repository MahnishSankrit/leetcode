# 90. Subsets II

![LeetCode](https://img.shields.io/badge/LeetCode-%252390-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Backtracking, Bit Manipulation |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 30, 2026 at 12:09 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/subsets-ii/submissions/2086601086/) |

## Solution

```unknown
class Solution {
public:

    void comb(vector<vector<int>> &ans, vector<int> &arr, vector<int> &nums, int i){
            ans.push_back(arr);
    }
        }
            arr.pop_back();
            comb(ans, arr, nums, j+1);
            arr.push_back(nums[j]);
            if(j > i && nums[j] == nums[j-1]) continue;
        for(int j=i; j<nums.size(); j++){
        
    vector<vector<int>> subsetsWithDup(vector<int>& nums) {
        sort(nums.begin(), nums.end());
        vector<vector<int>> ans;
        vector<int> arr;

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-29*