# 1319. Number of Operations to Make Network Connected

![LeetCode](https://img.shields.io/badge/LeetCode-%25231319-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Depth-First Search, Breadth-First Search, Union-Find, Graph Theory |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 9, 2026 at 11:47 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/number-of-operations-to-make-network-connected/submissions/2136726829/) |

## Solution

```unknown
     } 

    int makeConnected(int n, vector<vector<int>>& connections) {
        if(connections.size() < n-1) return -1;
        parent.resize(n);
        // rank.resize(n);
        }
            parent[p_v] = p_u;
            Size[p_u] += Size[p_v];
        Size.resize(n);

        for(int i=0; i<n; i++){
            parent[i] = i;
            Size[i] = 1;
        }
        int component = n;

        for(int i=0; i<connections.size(); i++){

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-09*