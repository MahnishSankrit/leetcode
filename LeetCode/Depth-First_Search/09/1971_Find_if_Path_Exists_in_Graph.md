# 1971. Find if Path Exists in Graph

![LeetCode](https://img.shields.io/badge/LeetCode-%25231971-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Depth-First Search, Breadth-First Search, Union-Find, Graph Theory |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 4, 2026 at 12:35 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/find-if-path-exists-in-graph/submissions/2130022932/) |

## Solution

```unknown
        while(!q.empty()){
            int node = q.front();
            q.pop();


        vector<int> visited(n, 0);
        q.push(source);
        queue<int> q;

        }
            adj[v].push_back(u);
            if(node == destination) return true;

            for(auto it : adj[node]){
                if(!visited[it]){
                    visited[it] = 1;
                    q.push(it);
                }
            adj[u].push_back(v);

            int v=it[1];
        visited[source] = 1;

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-03*