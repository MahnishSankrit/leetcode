# 3105. Longest Strictly Increasing or Strictly Decreasing Subarray

![LeetCode](https://img.shields.io/badge/LeetCode-%25233105-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 13, 2026 at 03:55 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/longest-strictly-increasing-or-strictly-decreasing-subarray/submissions/2194933005/) |

## Solution

```unknown
        for(int i=0; i<n; i++){
            for(int j=i; j<n; j++){
                vector<int> ans;
                for(int k=i+1; k<=j; k++){
                    if(nums[k] < nums[k-1]){
                        ans.push_back(nums[k]);
                    }else{
                }
            }
                        break;
                    }
        }
        return count;
    }
                int val = ans.size() + 1;
                count = max(count, val);
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-12*