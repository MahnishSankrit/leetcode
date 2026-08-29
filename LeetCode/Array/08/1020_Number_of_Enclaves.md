# 1020. Number of Enclaves

![LeetCode](https://img.shields.io/badge/LeetCode-%25231020-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Depth-First Search, Breadth-First Search, Union-Find, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 30, 2026 at 01:39 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/number-of-enclaves/submissions/2124319850/) |

## Solution

```unknown
            }
                }
                    visited[i][j] = 1;
                    q.push({i,j});
                if(grid[i][j] == 1 && (i == 0 || i == n-1 || j == 0 || j == m-1)){
        for(int i=0; i<n; i++){
            for(int j=0; j<m; j++){
        queue<pair<int, int>> q;


        vector<vector<int>> visited(n, vector<int>(m, 0));
        int n=grid.size();
        int m=grid[0].size();
class Solution {
public:
    int numEnclaves(vector<vector<int>>& grid) {

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-29*