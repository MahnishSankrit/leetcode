# 1312. Minimum Insertion Steps to Make a String Palindrome

![LeetCode](https://img.shields.io/badge/LeetCode-%25231312-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-red) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Hard |
| **Topics** | String, Dynamic Programming |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 21, 2026 at 11:56 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-insertion-steps-to-make-a-string-palindrome/submissions/2178255703/) |

## Solution

```unknown
            take = 2 + solveMemo(s, n, i+1, j-1, dp);
        if(s[i] == s[j]){
        int take = 0, skip1 = 0, skip2  = 0;

        if(dp[i][j] != -1) return dp[i][j];

        }else{
            skip1 = solveMemo(s, n , i , j -1, dp);
            skip2 = solveMemo(s, n, i+1, j, dp);
        }

        return dp[i][j] = max(take, max(skip1, skip2));
    }


    int minInsertions(string s) {
        int n=s.length();

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-21*