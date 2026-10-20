# 516. Longest Palindromic Subsequence

![LeetCode](https://img.shields.io/badge/LeetCode-%2523516-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String, Dynamic Programming |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 20, 2026 at 11:04 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/longest-palindromic-subsequence/) |

## Solution

```unknown
    // this is the recurson solution 

    int solve(string &s, int n, int i, string temp){
        if(i >= n){
            if(isPali(temp)){
                return temp.length();
            }
            return 0;
        }

        int take = solve(s, n, i+1, temp + s[i]);
    }
        return true;

        }
        int skip = solve(s, n, i+1, temp);


```

---
*Auto-synced by LeetCode Git Sync on 2026-10-20*