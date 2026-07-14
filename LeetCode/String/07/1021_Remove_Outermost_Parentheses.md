# 1021. Remove Outermost Parentheses

![LeetCode](https://img.shields.io/badge/LeetCode-%25231021-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | String, Stack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 14, 2026 at 03:02 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/remove-outermost-parentheses/submissions/2067178530/) |

## Solution

```unknown

        int count = 0;
        for(auto ch : s){
            if(ch == '('){
        }
                if(count > 0) res += ch;
            }else{
                count++;
                count--;
            }
    }
                if(count>0) res += ch;

        return res;
};
        string res = "";
    string removeOuterParentheses(string s) {
public:

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-14*