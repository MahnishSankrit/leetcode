# 152. Maximum Product Subarray

![LeetCode](https://img.shields.io/badge/LeetCode-%2523152-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 10, 2026 at 02:36 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/maximum-product-subarray/submissions/2062227087/) |

## Solution

```unknown
        for(int i=0; i<n; i++){
            if(pre == 0) pre = 1;
        }
            if(suf == 0) suf = 1;

            pre *= nums[i];
            suf *= nums[n-1-i];

            maxProd = max(max(pre, suf), maxProd);

        return maxProd;
        int maxProd = nums[0];
        
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-09*