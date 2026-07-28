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
| **Submitted** | July 28, 2026 at 11:28 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/combination-sum-ii/submissions/2085188624/) |

## Solution

```unknown
        if(i == nums.size()) return;
            return;
        }
            ans.push_back(arr);
        if(sum > k) return;
        if(sum == k){
 
    void comb(vector<vector<int>> &ans, vector<int> &arr, vector<int> &nums, int k, int i, int sum){

        for(int j=i; j<nums.size(); j++){
            if(i < j && nums[j] == nums[j-1]) continue;

            comb(ans, arr, nums, k, j+1, sum+nums[j]);
            arr.push_back(nums[j]);
public:
class Solution {

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-28*