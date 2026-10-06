# 921. Minimum Add to Make Parentheses Valid

![LeetCode](https://img.shields.io/badge/LeetCode-%2523921-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String, Stack, Greedy, Bracket Sequences |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 6, 2026 at 05:26 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid/submissions/2164188676/) |

## Solution

```unknown
                    count++;
                }
            }
        }

        if(!st.empty()){
            return count + st.size();
        }
        return count;
        
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-06*