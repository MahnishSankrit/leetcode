# 1631. Path With Minimum Effort

![LeetCode](https://img.shields.io/badge/LeetCode-%25231631-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Binary Search, Depth-First Search, Breadth-First Search, Union-Find, Heap (Priority Queue), Matrix, Dijkstra's Algorithm |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 5, 2026 at 06:08 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/path-with-minimum-effort/submissions/2131706266/) |

## Solution

```unknown
                int nx = cx + dx[i];
            for(int i=0; i<4; i++){

            // if(cx == n-1 && cy == m-1) return cost;

            q.pop();
            int cy = q.front().second.second;
            int cx = q.front().second.first;
            int cost = q.front().first;
        while(!q.empty()){

        int dy[] = {0, -1, 0, 1};
        int dx[] = {-1, 0 ,1 , 0};

        distance[0][0] = 0;
        q.push({0, {0, 0}});
        
        vector<vector<int>>distance(n, vector<int>(m, -1));
        queue<pair<int, pair<int, int>>> q;
        int m=heights[0].size();
        int n=heights.size();

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-05*