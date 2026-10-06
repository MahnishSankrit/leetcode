# 49. Group Anagrams

![LeetCode](https://img.shields.io/badge/LeetCode-%252349-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Hash Table, String, Sorting |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 6, 2026 at 10:55 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/group-anagrams/submissions/2164530504/) |

## Solution

```unknown
        for(int i=0; i<n; i++){
            sort(strs[i].begin(), strs[i].end());

            string t = strs[i];

        unordered_map<string, vector<string>> mp;
        int n=strs.size();
        vector<vector<string>> ans;
    vector<vector<string>> groupAnagrams(vector<string>& strs) {
public:
class Solution {
 // this problem look tough but it is easy as we know that in anargram if we sort the two 
 string and if they are equal then they are anargram else not and here we will use the same 
 idea to solve this we will have a map of string and vector string so that for the samae 
 sorted string will act as the key and the vlause will be the value of that string and at last 
 we will loop through on the map and store in the ans vector and return the ans;

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-06*