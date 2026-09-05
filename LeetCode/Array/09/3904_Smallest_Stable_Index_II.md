# 3904. Smallest Stable Index II

![LeetCode](https://img.shields.io/badge/LeetCode-%25233904-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Prefix Sum |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 6, 2026 at 12:18 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/smallest-stable-index-ii/submissions/2132077102/) |

## Solution

```unknown

        vector<int> prefix(n);
        prefix[0] = nums[0];
        for(int i=1; i<n; i++){
            prefix[i] = max(prefix[i-1], nums[i]);
        }

        vector<int> suffix(n);
        suffix[n-1] = nums[n-1];

        for(int i=n-2; i>=0; i--){
            suffix[i] = min(suffix[i+1], nums[i]);
        }

        for(int i=0; i<n; i++){
            if(prefix[i] - suffix[i] <= k) return i;
        }
    }

        return -1;
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-05*