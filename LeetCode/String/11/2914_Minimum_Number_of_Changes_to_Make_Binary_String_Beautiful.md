# 2914. Minimum Number of Changes to Make Binary String Beautiful

![LeetCode](https://img.shields.io/badge/LeetCode-%25232914-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 19, 2026 at 03:01 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-number-of-changes-to-make-binary-string-beautiful/submissions/2198967230/) |

## Solution

```unknown
class Solution {
public:
    int minChanges(string s) {
        int n=s.length();
        int count = 0;

        for(int i=1; i<n; i+=2){
            if(s[i] != s[i-1]) count++;
        }
    }

        return count;
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-18*