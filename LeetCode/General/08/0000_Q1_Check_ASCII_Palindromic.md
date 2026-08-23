# . Q1. Check ASCII Palindromic

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 23, 2026 at 10:31 PM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-516/problems/check-ascii-palindromic/submissions/2117605696/) |

## Solution

```unknown
1class Solution {
2public:
3    bool isPalindromic(string s) {
4        string val = "";
5        int n = s.length();
6
7        for(int i=0; i<n; i++){
8            int num = s[i];
9            bitset<8> binary(num);
10            val += binary.to_string();
11        }
12
13        int m = val.size();
14        for(int i=0; i<m; i++){
15            if(val[i] != val[m-i-1]) return false;
16        }
17
18        return true;
19    }
20};
```

---
*Auto-synced by LeetCode Git Sync on 2026-08-23*