# 22. Generate Parentheses

![LeetCode](https://img.shields.io/badge/LeetCode-%252322-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String, Dynamic Programming, Backtracking, Bracket Sequences |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 3, 2026 at 01:22 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/generate-parentheses/) |

## Solution

```unknown
    }
    void solve(int n, string temp, vector<string> &ans){
        if(temp.length() == 2 * n){
            if(check(temp)){
                ans.push_back(temp);
            }
            return;
        }
        
        solve(n, temp+'(', ans);
        // temp="";
        solve(n, temp+')', ans);

    }
    vector<string> generateParenthesis(int n) {
        vector<string> ans;
        solve(n, "", ans);

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-02*