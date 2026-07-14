# 451. Sort Characters By Frequency

![LeetCode](https://img.shields.io/badge/LeetCode-%2523451-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Hash Table, String, Sorting, Heap (Priority Queue), Bucket Sort, Counting |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 14, 2026 at 05:11 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/sort-characters-by-frequency/submissions/2067302079/) |

## Solution

```unknown
class Solution {
public:
    string frequencySort(string s) {
        unordered_map<char, int> mp;
        for(auto ch : s){
            mp[ch]++;
        }

        sort(s.begin(), s.end(), [&](char a, char b){
                if(mp[a] == mp[b]){
        });

        return s;
            
            return mp[a] > mp[b];
                    return a <b;
                }
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-14*