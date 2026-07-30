# 131. Palindrome Partitioning

![LeetCode](https://img.shields.io/badge/LeetCode-%2523131-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String, Dynamic Programming, Backtracking |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 31, 2026 at 01:05 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/palindrome-partitioning/submissions/2088005166/) |

## Solution

```unknown
                return;
                ans.push_back(temp);
            if(i == s.length()){
    void comb(vector<vector<string>> &ans, vector<string> &temp, string &s, int i){

            }    

            for(int j=i; j<s.length(); j++){
                if(isPali(s, i, j)){
                    temp.push_back(s.substr(i, j-i+1));
                    comb(ans, temp, s, j+1);
                    temp.pop_back();
                }
            }
    }
    vector<vector<string>> partition(string s) {
        vector<vector<string>> ans;

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-30*