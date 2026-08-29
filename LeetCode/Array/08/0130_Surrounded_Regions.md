# 130. Surrounded Regions

![LeetCode](https://img.shields.io/badge/LeetCode-%2523130-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Depth-First Search, Breadth-First Search, Union-Find, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 30, 2026 at 12:40 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/surrounded-regions/submissions/2124281869/) |

## Solution

```unknown
            }
                }
                    visited[i][j] = 1;
                    q.push({i, j});
                if(board[i][j] == 'O' && (i == 0 || i == n-1 || j == 0 || j == m-1)){
            for(int j=0; j<m; j++){
        for(int i=0; i<n; i++){

        queue<pair<int, int>> q;
        }

        int dx[] = {-1, 0, 1, 0};
        int dy[] = {0, -1, 0, 1};

        while(!q.empty()){
        vector<vector<int>> visited(n, vector<int>(m, 0));


```

---
*Auto-synced by LeetCode Git Sync on 2026-08-29*