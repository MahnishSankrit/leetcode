# 207. Course Schedule

![LeetCode](https://img.shields.io/badge/LeetCode-%2523207-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Depth-First Search, Breadth-First Search, Graph Theory, Topological Sort, Directed Acyclic Graph |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 31, 2026 at 11:51 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/course-schedule/) |

## Solution

```unknown
            }
        }
        int count = 0;
        while(!q.empty()){
            int node = q.front();
            q.pop();
            count++;
            
            for(auto it : adj[node]){
                indegree[it]--;
                if(indegree[it] == 0){
                    q.push(it);
                }
            }
        }

        return count == n;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-31*