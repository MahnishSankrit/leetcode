# 216. Combination Sum III

![LeetCode](https://img.shields.io/badge/LeetCode-%2523216-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Backtracking |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 30, 2026 at 01:50 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/combination-sum-iii/submissions/2086682044/) |

## Solution

```unknown
    }

        arr.push_back(i);
        comb(ans, arr, k, n, i+1, sum+i);
        arr.pop_back();
        comb(ans, arr, k, n, i+1, sum);
        }
            return;
            ans.push_back(arr);
        if(sum == n && arr.size() == k){
        if(arr.size() > k) return;
        if(i > 10) return;
    void comb(vector<vector<int>> &ans, vector<int> &arr, int k, int n, int i, int sum){
public:
        if(sum > n) return;

    vector<vector<int>> combinationSum3(int k, int n) {
        vector<vector<int>> ans;

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-29*