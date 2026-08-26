# 994. Rotting Oranges

![LeetCode](https://img.shields.io/badge/LeetCode-%2523994-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Breadth-First Search, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 27, 2026 at 01:21 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/rotting-oranges/submissions/2121250172/) |

## Solution

```unknown
            for(int j=0; j<m; j++){
        int count = 0;
        bool find = false;
        for(int i=0; i<n; i++){
        queue<pair<int, int>> q;
        vector<vector<bool>> visited(n,vector<bool>(m, false));

       
        int dy[] = {-1,0,1,0};
        int dx[] = {0, -1, 0, 1};
        int n=grid.size();
        int m=grid[0].size();
    int orangesRotting(vector<vector<int>>& grid) {
        int time = 0;
public:
class Solution {

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-26*