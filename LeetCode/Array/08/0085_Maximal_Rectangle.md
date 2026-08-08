# 85. Maximal Rectangle

![LeetCode](https://img.shields.io/badge/LeetCode-%252385-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-red) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Hard |
| **Topics** | Array, Dynamic Programming, Stack, Matrix, Monotonic Stack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 8, 2026 at 04:00 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/maximal-rectangle/submissions/2098973575/) |

## Solution

```unknown
        vector<int> nums(m, 0);

        int maxArea = INT_MIN;

        for (int i = 0; i < n; i++) {
            for (int j = 0; j < m; j++) {
                if (matrix[i][j] == '0') {
                    nums[j] = 0;
                } else {
                    nums[j]++;
                }
            }
            int val = area(nums);

            maxArea = max(val, maxArea);
        }
    return maxArea;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-08*