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
| **Submitted** | October 20, 2026 at 10:14 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/longest-common-subsequence/submissions/2177256364/) |

## Solution

```unknown
        }

        return max(take, max(skip1, skip2));
            skip2 = solve(s1, s2, i+1, j, n, m); 
            skip1 =  solve(s1, s2, i, j+1, n, m);
        }else{
            take = 1 +  solve(s1, s2, i+1, j+1, n, m);
        if(s1[i] == s2[j]){
        int skip2 = 0;

    }
    int longestCommonSubsequence(string text1, string text2) {
        int n=text1.size();
        int m=text2.size();

        return solve(text1, text2, 0, 0, n, m);
    }

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-20*