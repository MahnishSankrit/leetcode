# 496. Next Greater Element I

![LeetCode](https://img.shields.io/badge/LeetCode-%2523496-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Hash Table, Stack, Monotonic Stack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 4, 2026 at 11:46 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/next-greater-element-i/submissions/2094455693/) |

## Solution

```unknown
        }
            }

                }
        vector<int> ans;
        for(int i=0; i<n1; i++){
            if(mp.find(nums1[i]) != mp.end()){
                ans.push_back(mp[nums1[i]]);
            }else{
                ans.push_back(-1);
            }
        }

        return ans;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-04*