# 1614. Maximum Nesting Depth of the Parentheses

![LeetCode](https://img.shields.io/badge/LeetCode-%25231614-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | String, Stack, Bracket Sequences |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 28, 2026 at 11:34 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/maximum-nesting-depth-of-the-parentheses/submissions/2156325293/) |

## Solution

```unknown
        for(int i=0; i<n; i++){
            if(s[i] == '('){
                count++;
            }else{
                if(s[i] == ')'){
                    maxCount = max(count, maxCount);
                    count--;
                }
            }
        }
        if(maxCount == INT_MIN) return 0;

        int maxCount = INT_MIN;
        int count = 0;
        int n=s.length();
    int maxDepth(string s) {
public:

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-28*