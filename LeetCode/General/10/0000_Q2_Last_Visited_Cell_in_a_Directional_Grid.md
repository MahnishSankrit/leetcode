# . Q2. Last Visited Cell in a Directional Grid

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 19, 2026 at 12:06 AM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-524/problems/last-visited-cell-in-a-directional-grid/submissions/2175658298/) |

## Solution

```unknown
1class Solution {
2public:
3    vector<int> lastVisitedCell(vector<vector<char>>& grid) {
4        vector<int> ans;
5        int n = grid.size();
6        int m = grid[0].size();
7        unordered_map<char, pair<int, int>> mp = {
8            {'R', {0, 1}}, {'L', {0, -1}}, {'D', {1, 0}}, {'U', {-1, 0}}};
9
10        vector<vector<int>> visited(n, vector<int>(m, 0));
11
12        int i = 0, j = 0;
13        visited[i][j] = 1;
14        while (true) {
15
16            int nx = i + mp[grid[i][j]].first;
17            int ny = j + mp[grid[i][j]].second;
18            if (nx >= 0 && ny >= 0 && nx < n && ny < m) {
19                if (!visited[nx][ny]) {
20                    i = nx;
21                    j = ny;
22                    visited[nx][ny] = 1;
23                } else {
24                    return {i, j};
25                }
26            }else{
27                return {i, j};
28            }
29            
30        }
31
32        return ans;
33    }
34};
```

---
*Auto-synced by LeetCode Git Sync on 2026-10-18*