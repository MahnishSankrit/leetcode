# 40. Combination Sum II

![LeetCode](https://img.shields.io/badge/LeetCode-%252340-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Backtracking |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 27, 2026 at 11:54 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/combination-sum-ii/) |

## Solution

```unknown
        // if(!arr.empty()){
            arr.pop_back();
        // }
        // if(sum < k){
            arr.push_back(nums[i]);
            comb(ans, arr, nums, k, i+1, sum + nums[i]);
        if(i == nums.size()) return;
        }
            return;
            ans.insert(arr);
        if(sum == k){
        // this problem is going to give me the tle 
public:
    void comb(set<vector<int>> &ans, vector<int> &arr, vector<int> &nums, int k, int i, int sum){
class Solution {
        if(sum > k) return;

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-27*