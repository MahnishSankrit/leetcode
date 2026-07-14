# 796. Rotate String

![LeetCode](https://img.shields.io/badge/LeetCode-%2523796-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | String, String Matching |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 14, 2026 at 04:54 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/rotate-string/) |

## Solution

```unknown
class Solution {
public:
    bool rotateString(string s, string goal) {
        int n=s.length();
        for(int i=0; i<n; i++){
            if(s != goal){
                rotate(s.begin(), s.begin() + 1, s.end());
            }else{
                return true;
            }
        }

        return false;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-14*