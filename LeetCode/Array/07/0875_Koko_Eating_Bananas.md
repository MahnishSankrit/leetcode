# 875. Koko Eating Bananas

![LeetCode](https://img.shields.io/badge/LeetCode-%2523875-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Binary Search |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 13, 2026 at 04:28 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/koko-eating-bananas/submissions/2066035500/) |

## Solution

```unknown
        while(low <= high){

        int ans= INT_MAX;
        int high = maxVal;
        int low = 1;

        // binary search apply

        }
            maxVal = max(maxVal, piles[i]);
            int mid = low + (high - low)/2;
            long long val = ceilFunc(piles, mid);

            if(val <= h){
                // ans = min(ans, mid);
                ans = mid;
                high = mid  -1;
            }else if(val > h){
                low = mid + 1;
            }

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-13*