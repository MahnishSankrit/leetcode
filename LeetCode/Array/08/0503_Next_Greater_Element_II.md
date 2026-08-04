# 503. Next Greater Element II

![LeetCode](https://img.shields.io/badge/LeetCode-%2523503-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Stack, Monotonic Stack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 5, 2026 at 01:12 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/next-greater-element-ii/submissions/2094547594/) |

## Solution

```unknown
                if (st.empty())
                    ans.push_back(-1);
                else
                    ans.push_back(st.top());
            }

            st.push(nums[i % n]);
        }

        reverse(ans.begin(), ans.end());
        return ans;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-04*