# 494. Target Sum

![LeetCode](https://img.shields.io/badge/LeetCode-%2523494-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming, Backtracking, Knapsack Problem, 0-1 Knapsack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 29, 2026 at 11:46 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/target-sum/) |

## Solution

```unknown
    
    int findTargetSumWays(vector<int>& nums, int target) {
    }
        int take = solve(nums, target, i+1, sum + nums[i], n);
        int notTake = solve(nums, target, i+1, sum - nums[i], n);

        return take + notTake;

        }
            return 0;
            if(sum == target) return 1;
        if(i >= n){
    int solve(vector<int> &nums, int target, int i, int sum ,int n){
public:
class Solution {
// this is the recursive way to solve this 

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-29*