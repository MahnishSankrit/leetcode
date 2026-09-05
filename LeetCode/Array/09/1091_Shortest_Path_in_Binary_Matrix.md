# 1091. Shortest Path in Binary Matrix

![LeetCode](https://img.shields.io/badge/LeetCode-%25231091-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Breadth-First Search, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 5, 2026 at 05:17 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/shortest-path-in-binary-matrix/submissions/2131664690/) |

## Solution

```unknown
            for(int i=0; i<8; i++){
                int nx = cx + dx[i];
                int ny = cy + dy[i];
                

                if(nx>=0 && ny>=0 && nx<n && ny<m  && grid[nx][ny] == 0){
                    // visited[nx][ny] = 1;
                    if(dist[nx][ny] == -1 ||  dist[nx][ny] > distance + 1){
                        dist[nx][ny] = distance + 1;
                        pq.push({dist[nx][ny], {nx, ny}});
                    }
                }
            }
        }
        return -1;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-05*