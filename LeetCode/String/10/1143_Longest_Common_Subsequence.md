# 1143. Longest Common Subsequence

![LeetCode](https://img.shields.io/badge/LeetCode-%25231143-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String, Dynamic Programming, Longest Common Subsequence |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 11, 2026 at 12:29 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/longest-common-subsequence/submissions/2168573915/) |

## Solution

```unknown
            solve(text1, text2, n1, n2, i, j+1, temp, maxi);
            solve(text1, text2, n1, n2, i+1, j, temp, maxi);
        }else{
            temp.pop_back();
            solve(text1, text2, n1, n2, i+1, j+1, temp, maxi);
            temp.push_back(text1[i]);
        if(text1[i] == text2[j]){
        
        }
            return;
        if(i == n1 || j == n2){
        maxi = max(maxi, (int)temp.length());
    maxi){
    void solve(string text1, string text2, int n1, int n2, int i, int j, string &temp, int &
class Solution {
public:

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-10*