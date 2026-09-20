# 3498. Reverse Degree of a String

![LeetCode](https://img.shields.io/badge/LeetCode-%25233498-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | String, Simulation |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 21, 2026 at 12:23 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/reverse-degree-of-a-string/submissions/2148019857/) |

## Solution

```unknown
             {'y', 2},  {'z', 1}});

        int n=s.length();

        int val = 0;
        for(int i=0; i<n; i++){
            int sum = mp[s[i]] * (i+1);
            // val += mp[s[i]] * i;
             {'s', 8},  {'t', 7},  {'u', 6},  {'v', 5},  {'w', 4},  {'x', 3},
             {'m', 14}, {'n', 13}, {'o', 12}, {'p', 11}, {'q', 10}, {'r', 9},
             {'g', 20}, {'h', 19}, {'i', 18}, {'j', 17}, {'k', 16}, {'l', 15},
            {{'a', 26}, {'b', 25}, {'c', 24}, {'d', 23}, {'e', 22}, {'f', 21},
        unordered_map<char, int> mp(
            val += sum;
        }

        return val;

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-20*