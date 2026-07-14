# 205. Isomorphic Strings

![LeetCode](https://img.shields.io/badge/LeetCode-%2523205-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Hash Table, String |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 14, 2026 at 04:46 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/isomorphic-strings/) |

## Solution

```unknown
class Solution {
public:
    bool isIsomorphic(string s, string t) {
        unordered_map<char, char> mp1;
        unordered_map<char, char> mp2;

        int n=s.length();
        int m=t.length();

        for(int i=0; i<n; i++){
            if(mp1.find(s[i]) == mp1.end()){ 
                // if not exist then make a mapp to them
                mp1[s[i]] = t[i];
            }else{
                if(mp1[s[i]] != t[i]){ // if already existe then return false;1
                    return false;
                }
            }


```

---
*Auto-synced by LeetCode Git Sync on 2026-07-14*