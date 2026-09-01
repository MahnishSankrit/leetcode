# 210. Course Schedule II

![LeetCode](https://img.shields.io/badge/LeetCode-%2523210-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Depth-First Search, Breadth-First Search, Graph Theory, Topological Sort |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 1, 2026 at 11:36 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/course-schedule-ii/submissions/2127606277/) |

## Solution

```unknown
        //         visited[i] = 1;
        //         break;
        //     }
        // }

        for(int i=0; i<numCourses; i++){
            if(indegree[i] == 0 && visited[i] == 0){
                // arr.push_back(i);
        //         arr.push_back(i);
        //     if(indegree[i] == 0){
        // for(int i=0; i<numCourses; i++){
                dfs(indegree, i, visited, adj, -1, arr) ;
            }   
        }

        if(arr.size() != numCourses) return {};
        return arr;
    }

};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-01*