# 20. Valid Parentheses

![LeetCode](https://img.shields.io/badge/LeetCode-%252320-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | String, Stack, Bracket Sequences |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 4, 2026 at 12:57 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/valid-parentheses/submissions/2093150918/) |

## Solution

```unknown
            }else{
                if(st.empty()) {
                    return false;
                }else{
                    if((st.top() == '(' && s[i] == ')') || (st.top() == '[' && s[i] == ']') || (st.top
                    () == '{' && s[i] == '}') ){
                        st.pop();
                st.push(s[i]);
                    }else{
                        return false;
                    }
                }

            }
        }
        return true;
        if(!st.empty()) return false;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-03*