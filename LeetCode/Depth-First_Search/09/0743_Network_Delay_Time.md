# 743. Network Delay Time

![LeetCode](https://img.shields.io/badge/LeetCode-%2523743-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Depth-First Search, Breadth-First Search, Graph Theory, Heap (Priority Queue), Shortest Path, Dijkstra's Algorithm |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 7, 2026 at 11:34 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/network-delay-time/submissions/2134261993/) |

## Solution

```unknown
            int node = pq.top().second;
            pq.pop();

            for(auto it : adj[node]){
                int vertex = it.first;
                int wt = it.second;
            int cost = pq.top().first;
        while(!pq.empty()){
                if(dist[vertex] == INT_MAX || dist[vertex] > cost +  wt){
                    dist[vertex] = cost + wt;
                    pq.push({dist[vertex], vertex});
                }
            }
        }

        int ans = 0;
        for(int i=1; i<=n; i++){

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-07*