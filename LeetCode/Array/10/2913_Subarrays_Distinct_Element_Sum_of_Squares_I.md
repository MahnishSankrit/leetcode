# 2913. Subarrays Distinct Element Sum of Squares I

![LeetCode](https://img.shields.io/badge/LeetCode-%25232913-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Hash Table, Binary Indexed Tree, Segment Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 15, 2026 at 12:01 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/subarrays-distinct-element-sum-of-squares-i/submissions/2172774817/) |

## Solution

```unknown
        for(int i=0; i<n; i++){
            for(int j=i; j<n; j++){
                set<int> st;
            }
                for(int k=i; k<=j; k++){
                    st.insert(nums[k]);
                }
                int size = st.size();
                sum += size * size;

        }

        return sum;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-15*