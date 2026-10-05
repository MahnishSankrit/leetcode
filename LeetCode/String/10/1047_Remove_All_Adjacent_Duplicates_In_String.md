# 1047. Remove All Adjacent Duplicates In String

![LeetCode](https://img.shields.io/badge/LeetCode-%25231047-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | String, Stack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 6, 2026 at 02:00 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/submissions/2163584210/) |

## Solution

```unknown
        int n=s.length();
        string t="";

        // solve(s, t, 0, n);
        for(int i=0; i<n; i++){
            if(t.empty()){
                t.push_back(s[i]);
            }else if(!t.empty() && t.back() == s[i]){
                t.pop_back();
            }else{
        }
        
        return t;
       
    string removeDuplicates(string s) {
                t.push_back(s[i]);
            }

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-05*