# . Q1. Even Number of Knight Moves

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 19, 2026 at 11:46 AM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-511/problems/even-number-of-knight-moves/submissions/2073131066/) |

## Solution

```unknown
1class Solution {
2public:
3    bool canReach(vector<int>& start, vector<int>& target) {
4        return ((start[0] + start[1]) % 2) == ((target[0] + target[1]) % 2);
5        // BADA HEE MADHERCHOD QUESTION HAI YE 
6        // DIRECT FORMULA AND MATH BASED APPROACH HAI, AND I THOUGHT GRAPH TRAVERSE KARNA HOGA 
7    }
8};
```

---
*Auto-synced by LeetCode Git Sync on 2026-07-19*