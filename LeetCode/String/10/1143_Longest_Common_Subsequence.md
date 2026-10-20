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
| **Submitted** | October 20, 2026 at 10:31 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/longest-common-subsequence/submissions/2177272131/) |

## Solution

```unknown
                    skip1 = dp[i][j+1];
                    skip2 = dp[i+1][j];
                }
                }else{
                    take  = 1 + dp[i+1][j+1];
                if(text1[i] == text2[j]){

                int skip2 = 0;
                int skip1 =0;
                int take = 0;
            for(int j=m-1; j>=0; j--){
        for(int i=n-1; i>=0; i--){

        dp[n][m] = 0;
        vector<vector<int>> dp(n+1, vector<int>(m+1, 0));
        // tabulatiion

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-20*