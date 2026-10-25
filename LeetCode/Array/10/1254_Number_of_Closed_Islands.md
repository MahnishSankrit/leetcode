# 1254. Number of Closed Islands

![LeetCode](https://img.shields.io/badge/LeetCode-%25231254-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Depth-First Search, Breadth-First Search, Union-Find, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 26, 2026 at 12:24 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/number-of-closed-islands/submissions/2181674920/) |

## Solution

```unknown
                            closed = false;
                        }

                        for (int i = 0; i < 4; i++) {
                            int nx = dx[i] + cx;
                            int ny = dy[i] + cy;

                            if (nx >= 0 && ny >= 0 && nx < n && ny < m &&
                                grid[nx][ny] == 0 && !visited[nx][ny]) {
                                visited[nx][ny] = true;
                                q.push({nx, ny});
                            }
                        }
                    }
                        if (closed) count++;
                }
            }

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-25*