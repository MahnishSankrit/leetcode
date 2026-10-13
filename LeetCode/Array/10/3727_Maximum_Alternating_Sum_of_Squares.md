# 3727. Maximum Alternating Sum of Squares

![LeetCode](https://img.shields.io/badge/LeetCode-%25233727-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Greedy, Sorting |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 13, 2026 at 11:53 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/maximum-alternating-sum-of-squares/submissions/2171501140/) |

## Solution

```unknown
        }
        sort(ans.begin(), ans.end(), greater<int>());

            }

        for(int i=0; i<(n+1)/2; i++){
            sum += ans[i] * ans[i];
        }
                ans.push_back(nums[i]);
            }else{
       

        for(int i=(n+1)/2; i<n; i++){
            diff += ans[i] * ans[i];
        }

        return sum - diff;

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-13*