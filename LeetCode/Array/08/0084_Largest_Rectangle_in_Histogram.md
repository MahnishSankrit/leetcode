# 84. Largest Rectangle in Histogram

![LeetCode](https://img.shields.io/badge/LeetCode-%252384-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-red) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Hard |
| **Topics** | Array, Stack, Monotonic Stack, Range Minimum/Maximum Query |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 7, 2026 at 06:56 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/largest-rectangle-in-histogram/submissions/2097984932/) |

## Solution

```unknown
        rightmini(heights, right);
        int area = 0;

        for(int i=0; i<n; i++){
            int width = right[i] - left[i] - 1;
            area = max(width * heights[i] , area);
        }

        return area;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-07*