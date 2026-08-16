# . Q1. Nearest Available Drone

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 16, 2026 at 01:31 PM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-515/problems/nearest-available-drone/submissions/2108719493/) |

## Solution

```unknown
1class Solution {
2public:
3    int nearestDrone(vector<vector<int>>& drones, vector<int>& target) {
4        int n=drones.size();
5        int m=drones[0].size();
6        int minInd = INT_MAX;
7        int minSum = INT_MAX;
8        for(int i=0; i<n; i++){
9            int sum = abs(drones[i][0] - target[0])  +  abs(drones[i][1] - target[1]); 
10            // if(sum == minSum) break;
11            if(sum <= drones[i][2]){
12                if(sum < minSum){
13                    minSum = sum;
14                    minInd = i;    
15                }
16                
17            } 
18        }
19        if(minInd == INT_MAX) return -1;
20        return minInd;
21    }
22};
```

---
*Auto-synced by LeetCode Git Sync on 2026-08-16*