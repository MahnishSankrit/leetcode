# . Q1. Count Consistent Subarrays I

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 16, 2026 at 11:24 PM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-528/problems/count-consistent-subarrays-i/submissions/2197507489/) |

## Solution

```unknown
1class Solution {
2public:
3    int countConsistent(vector<int>& nums) {
4        int n=nums.size();
5        // int i=0;
6        // int j=0;
7        // int mini = nums[0];
8        // int and= 0;
9        // int count = 0;
10        // while(i < n){
11        //     and &= nums[i];
12        //     if(and == mini){
13        //         count++;
14        //     }
15        // }
16
17        int count = 0;
18        for(int i=0; i<n; i++){
19            int mini = INT_MAX;
20            int add = nums[i];
21            for(int j=i; j<n; j++){
22                mini = min(mini, nums[j]);
23                add &= nums[j];
24                if(add == mini) count++;
25            }
26        }
27
28        return count;
29    }
30};
```

---
*Auto-synced by LeetCode Git Sync on 2026-11-16*