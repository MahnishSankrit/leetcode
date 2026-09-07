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
| **Submitted** | September 7, 2026 at 11:10 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/network-delay-time/submissions/2134229617/) |

## Solution

```unknown

        dist[k] = 0;
        q.push({0, k});
        queue<pair<int,int>> q;
        vector<int> dist(n+1, INT_MAX);

        }
            adj[u].push_back({v, wt});
        while(!q.empty()){
            int cost = q.front().first;
            int node = q.front().second;
            q.pop();


            for(auto it : adj[node]){
                int wt = it.second;
                int vertex = it.first;

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-07*