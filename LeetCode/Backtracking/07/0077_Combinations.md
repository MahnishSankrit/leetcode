# 77. Combinations

![LeetCode](https://img.shields.io/badge/LeetCode-%252377-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Backtracking |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 27, 2026 at 10:54 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/combinations/submissions/2083729484/) |

## Solution

```unknown
        // arr.push_back(i);
        comb(ans, n, k, i+1, arr);
        arr.pop_back();
        comb(ans, n, k, i+1, arr);
        arr.push_back(i+1);
        }
            return;
            ans.push_back(arr);
        if(arr.size() == k){
        
            }
                return;
      
        
    }
    vector<vector<int>> combine(int n, int k) {
        vector<vector<int>> ans;

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-27*