# 1541. Minimum Insertions to Balance a Parentheses String

![LeetCode](https://img.shields.io/badge/LeetCode-%25231541-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String, Stack, Greedy, Bracket Sequences |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 10, 2026 at 02:42 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-insertions-to-balance-a-parentheses-string/submissions/2167678084/) |

## Solution

```unknown
               if(!st.empty()){
                st.pop();
               }else{
                count++;
               }
            }
        }
        
        count += 2 * st.size();
        return count;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-09*