# 2104. Sum of Subarray Ranges

![LeetCode](https://img.shields.io/badge/LeetCode-%25232104-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Stack, Monotonic Stack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 7, 2026 at 12:57 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/sum-of-subarray-ranges/submissions/2097209369/) |

## Solution

```unknown
                }
                if (st.empty()) {
                    right[i] = n;
                    st.push(i);
                } else {
                    st.pop();
                while (!st.empty() && nums[st.top()] < nums[i]) {
            } else {
                st.push(i);
                right[i] = n;
            if (st.empty()) {
                    right[i] = st.top();
                    st.push(i);
                }
            }
        }
        return right;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-06*