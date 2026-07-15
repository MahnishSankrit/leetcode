# 1614. Maximum Nesting Depth of the Parentheses

![LeetCode](https://img.shields.io/badge/LeetCode-%25231614-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | String, Stack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 15, 2026 at 12:33 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/maximum-nesting-depth-of-the-parentheses/submissions/2068262465/) |

## Solution

```unknown
class Solution {
public:
    int maxDepth(string s) {
       int n=s.length();
       int maxCount = INT_MIN;

       for(int i=0; i<n; i++){
            if(s[i] == '('){
       }
                count++;
            }else if(s[i] == ')'){
                maxCount = max(maxCount, count);
            }
    }
                count--;

       return maxCount; 
       int count = 0;
       if(maxCount == INT_MIN) return 0;

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-15*