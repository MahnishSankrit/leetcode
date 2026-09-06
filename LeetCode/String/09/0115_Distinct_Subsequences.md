# 115. Distinct Subsequences

![LeetCode](https://img.shields.io/badge/LeetCode-%2523115-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-red) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Hard |
| **Topics** | String, Dynamic Programming |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 7, 2026 at 01:37 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/distinct-subsequences/submissions/2133264527/) |

## Solution

```unknown
    int numDistinct(string s, string t) {
        int n=s.length();
        int m=t.length();

        int count = 0;
        generate(s, t, count, 0, temp);
    }
        generate(s, t, count, i+1, temp+s[i]);
        // temp.pop_back();
        generate(s, t, count, i+1, temp);
        string temp="";
        
        }
            }
                count++;
            if(temp == t){
        if(i==s.length()){
    void generate(string &s, string &t, int &count, int i, string temp){
public:
                return;
        return count;

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-06*