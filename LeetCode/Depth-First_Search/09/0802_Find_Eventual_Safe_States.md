# 802. Find Eventual Safe States

![LeetCode](https://img.shields.io/badge/LeetCode-%2523802-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Depth-First Search, Breadth-First Search, Graph Theory, Topological Sort, Kosaraju's Algorithm, Tarjan's SCC Algorithm |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 1, 2026 at 11:55 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/find-eventual-safe-states/submissions/2127632824/) |

## Solution

```unknown
            adj[v].push_back(i);
            outdegree[i]++;

            }
        }
            
        vector<int> arr;
        vector<int> visited(n, 0);
        for(int i=0; i<n; i++){
            if(outdegree[i] == 0 && !visited[i]){
                safe(i, visited, adj, arr, outdegree);
            }
        }
        sort(arr.begin(), arr.end());
        return arr;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-01*