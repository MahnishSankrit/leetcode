# 3551. Minimum Swaps to Sort by Digit Sum

![LeetCode](https://img.shields.io/badge/LeetCode-%25233551-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Hash Table, Sorting |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 18, 2026 at 01:03 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-swaps-to-sort-by-digit-sum/submissions/2174851775/) |

## Solution

```unknown
            int db = digit(b);

            if (da != db) return da < db;

            return a < b;
        });

        unordered_map<int, int> mp;

        for (int i = 0; i < ans.size(); i++) {
            mp[ans[i]] = i;
        }

        int count = 0;

        for (int i = 0; i < temp.size(); i++) {
            if (temp[i] != ans[i]) {

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-17*