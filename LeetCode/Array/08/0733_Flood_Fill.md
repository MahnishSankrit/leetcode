# 733. Flood Fill

![LeetCode](https://img.shields.io/badge/LeetCode-%2523733-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Depth-First Search, Breadth-First Search, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 27, 2026 at 11:56 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/flood-fill/) |

## Solution

```unknown
            q.pop();

            for(int i=0; i<4; i++){
                int nx = cx + dx[i];
                int ny = cy + dy[i];

                if(nx >= 0 && ny >= 0 && nx < n && ny < m && image[nx][ny] == oldColor){
                    if(!visited[nx][ny]){
                        image[nx][ny] = newColor;
                        visited[nx][ny] = 1;
                        q.push({nx, ny});
                    }
                }
            }
        }

        return image;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-27*