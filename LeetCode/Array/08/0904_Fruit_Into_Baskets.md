# 904. Fruit Into Baskets

![LeetCode](https://img.shields.io/badge/LeetCode-%2523904-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Hash Table, Sliding Window |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 10, 2026 at 07:41 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/fruit-into-baskets/submissions/2101634683/) |

## Solution

```unknown
                    ans.push_back(nums[j]);
                }else if(ans.size() == 1 && ans[0] != nums[j]){
                    ans.push_back(nums[j]);
                if(ans.empty()){
            for(int j=i; j<n; j++){
                }else if(ans.size() == 2 && ans[0] != nums[j] && ans[1] != nums[j]){
                   break;
                } 
                len = max(len , j - i + 1);
            }
        }

        return len;

    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-10*