# 947. Most Stones Removed with Same Row or Column

![LeetCode](https://img.shields.io/badge/LeetCode-%2523947-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Hash Table, Depth-First Search, Union-Find, Graph Theory, Bipartite Graph |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 10, 2026 at 12:35 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/most-stones-removed-with-same-row-or-column/submissions/2136777818/) |

## Solution

```unknown
        parent.resize(n);
        size.resize(n);

        for(int i=0; i<n; i++){
            parent[i] = i;
            size[i] = 1;
        }
        int count = 0;
        for(int i=0; i<stones.size(); i++){
           for(int j=i+1; j<n; j++){
                 if(stones[i][0] == stones[j][0] || stones[i][1] == stones[j][1]) {
                    Union(i, j);
                }
           }
        }

        for(int i=0; i<n; i++){

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-09*