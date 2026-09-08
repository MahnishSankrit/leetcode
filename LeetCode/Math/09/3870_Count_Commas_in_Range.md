# 3870. Count Commas in Range

![LeetCode](https://img.shields.io/badge/LeetCode-%25233870-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Math |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 9, 2026 at 12:30 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/count-commas-in-range/submissions/2135557831/) |

## Solution

```unknown
class Solution {
public:
    int countCommas(int n) {
        
        // if(n >= 1000 && n < 10000){
        //     return n-1000 +1 ;
        // }else if(n >= 10000 && n < 100000){
        //     return n-1000 + 1;
        // }else if(n>=100000 && n < 1000000){
        return n - 1000 + 1;
        //     return n-1000 + 1;
        // }
    }
        if(n < 1000) return 0;
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-08*