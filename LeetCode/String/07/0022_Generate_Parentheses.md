# 22. Generate Parentheses

![LeetCode](https://img.shields.io/badge/LeetCode-%252322-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String, Dynamic Programming, Backtracking |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 25, 2026 at 11:23 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/generate-parentheses/submissions/2081082326/) |

## Solution

```unknown
        if(s.length() == 2*n){
            if(isValid(s)){
            ans.push_back(s);
            }
        }
        
    void generate(vector<string> &ans, int n, int i, string s){

        }
            return;
            return false;
            if(st.empty()) return true;
        s.push_back('(');
        generate(ans, n, i+1, s);
    
        s.pop_back();
            

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-25*