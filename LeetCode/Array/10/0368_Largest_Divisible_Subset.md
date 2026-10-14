# 368. Largest Divisible Subset

![LeetCode](https://img.shields.io/badge/LeetCode-%2523368-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Math, Dynamic Programming, Sorting |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 15, 2026 at 12:33 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/largest-divisible-subset/submissions/2172462244/) |

## Solution

```unknown

       solve(nums, arr,temp,n, i+1, j);
        }
            temp.pop_back();
            solve(nums, arr, temp, n, i+1, i);
            temp.push_back(nums[i]);
        if(j == -1 || nums[i] % nums[j] == 0){
       
        }
            return;
            }
                arr = temp;
            if(temp.size() > arr.size()){
        if(i == n){
    void solve(vector<int> &nums, vector<int> &arr, vector<int> &temp, int n, int i, int j){
    //t this si sth recursion + backtrackiong approach to solve the problem
public:

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-14*