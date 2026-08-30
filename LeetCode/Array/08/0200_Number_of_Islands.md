# 200. Number of Islands

![LeetCode](https://img.shields.io/badge/LeetCode-%2523200-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Depth-First Search, Breadth-First Search, Union-Find, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 30, 2026 at 11:57 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/number-of-islands/) |

## Solution

```unknown
        int dx[] = {-1, 0, 1, 0};
        int dy[] = {0, -1, 0, 1};
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < m; j++) {
                if (grid[i][j] == '1' && !visited[i][j]) {
                    count++;
                    q.push({i, j});
                    visited[i][j] = 1;
                }

                while (!q.empty()) {
                    auto [cx, cy] = q.front();
                    q.pop();

                    for (int i = 0; i < 4; i++) {
                        int nx = cx + dx[i];

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-30*