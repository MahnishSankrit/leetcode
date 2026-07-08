# 56. Merge Intervals

![LeetCode](https://img.shields.io/badge/LeetCode-%252356-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Sorting |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 8, 2026 at 08:33 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/merge-intervals/submissions/2060656143/) |

## Solution

```unknown
        vector<vector<int>> arr;
        for(int i=1; i<n; i++){
        
        }
        
        return arr;
        
        int n=intervals.size();
           if(intervals[i][0] <= arr.back()[1]){
            arr.back()[1] = max(intervals[i][1], arr.back()[1]);
           }else{
        arr.push_back(intervals[0]);
            arr.push_back(intervals[i]);
           }
        sort(intervals.begin(), intervals.end());
    vector<vector<int>> merge(vector<vector<int>>& intervals) {
public:
    }
class Solution {

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-08*