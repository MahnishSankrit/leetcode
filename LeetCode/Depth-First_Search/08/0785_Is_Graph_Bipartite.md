# 785. Is Graph Bipartite?

![LeetCode](https://img.shields.io/badge/LeetCode-%2523785-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Depth-First Search, Breadth-First Search, Union-Find, Graph Theory, Graph Coloring, Bipartite Graph |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 31, 2026 at 12:39 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/is-graph-bipartite/) |

## Solution

```unknown
        for (auto it : adj[node]) {

        color[node] = col;

            if (color[it] == -1) {
                if (dfs(it, !col, color, adj) == false)

                    return false;
            } else if (color[it] == col) {

                return false;
            }
        }
        return true;
    }

    bool isBipartite(vector<vector<int>>& graph) {

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-30*