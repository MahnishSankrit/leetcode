# 930. Binary Subarrays With Sum

![LeetCode](https://img.shields.io/badge/LeetCode-%2523930-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Hash Table, Sliding Window, Prefix Sum |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 12, 2026 at 10:50 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/binary-subarrays-with-sum/submissions/2104530725/) |

## Solution

```unknown
            if(mp.find(sum - goal) != mp.end()){
            sum += nums[i];
                count += mp[sum - goal];
            }

        for(int i=0; i<n; i++){
     
        mp[0] = 1;
        }
        return count;
    }
            mp[sum]++;
};
        unordered_map<int, int> mp;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-12*