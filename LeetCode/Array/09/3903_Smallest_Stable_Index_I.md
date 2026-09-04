# 3903. Smallest Stable Index I

![LeetCode](https://img.shields.io/badge/LeetCode-%25233903-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Prefix Sum |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 4, 2026 at 11:09 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/smallest-stable-index-i/submissions/2130984417/) |

## Solution

```unknown
    int firstStableIndex(vector<int>& nums, int k) {
        int n=nums.size();

        int maxVal = INT_MIN;
    
        for(int i=0; i<n; i++){
            maxVal = max(maxVal , nums[i]);
        }
            for(int j=i; j<n; j++){
                minVal = min(minVal, nums[j]);
            }
    }
            if(res  <= k) return i;
        return -1;
            int minVal = INT_MAX;
            int res = maxVal - minVal;
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-04*