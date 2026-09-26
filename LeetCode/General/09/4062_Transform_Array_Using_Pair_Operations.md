# 4062. Transform Array Using Pair Operations

![LeetCode](https://img.shields.io/badge/LeetCode-%25234062-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 26, 2026 at 09:45 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/transform-array-using-pair-operations/submissions/2154137874/) |

## Solution

```unknown
    bool canTransform(vector<int>& source, vector<int>& target) {
         int n=source.size();
     
        long long srcSum = 0;
        long long tarSum = 0;

        for(auto it : source){
            srcSum += it;
        }
        for(auto it : target){
            tarSum += it;
        }

        if(srcSum == tarSum) return true;
        return false;
    }

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-26*