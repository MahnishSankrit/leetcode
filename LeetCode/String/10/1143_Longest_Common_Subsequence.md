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
| **Submitted** | October 20, 2026 at 10:23 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/longest-common-subsequence/) |

## Solution

```unknown
            skip1 = solveMemo(s1, s2, i, j+1, n, m,dp);
        else {
        }
            take = 1  + solveMemo(s1, s2, i+1, j+1, n, m, dp);
        if(s1[i] == s2[j]){
        int take = 0, skip1 = 0, skip2 =0;

        if(dp[i][j]   !=  -1) return dp[i][j];
    {
        if(i >= n || j >= m) return 0;

    int solveMemo(string &s1, string &s2, int i, int j, int n, int m , vector<vector<int>> &dp)
    // this memo approch is also giving me the tle  casue i was passing both the string as the 
    // lets do the memonization here 

    // }
    refrence now it is not tle

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-20*