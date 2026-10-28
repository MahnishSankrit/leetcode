# 3963. Create Grid With Exactly One Path

![LeetCode](https://img.shields.io/badge/LeetCode-%25233963-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 28, 2026 at 10:33 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/create-grid-with-exactly-one-path/submissions/2184108056/) |

## Solution

```unknown
        for (int i = 0; i < m; i++) {
            for (int j = 0; j < n; j++) {
                if (i == 0) {
                    if (count != 0) {
                        grid[i][j] = '.';
                        count--;
                    } else {
                        grid[i][j] = '#';
                    }
                }

                if (i != 0 && j == 0) {
                    grid[i][j] = '#';
                }
            }
        }


```

---
*Auto-synced by LeetCode Git Sync on 2026-10-28*