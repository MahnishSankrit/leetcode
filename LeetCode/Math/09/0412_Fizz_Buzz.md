# 412. Fizz Buzz

![LeetCode](https://img.shields.io/badge/LeetCode-%2523412-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Math, String, Simulation |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 23, 2026 at 09:15 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/fizz-buzz/submissions/2151059740/) |

## Solution

```unknown
                ans.push_back("Fizz");
            }
            else if(i % 5 == 0){
                ans.push_back("Buzz");
            }else{
                ans.push_back(to_string(i));
            }
        }

        return ans;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-23*