# . Q1. Elevator Requests I

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 15, 2026 at 09:46 PM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/biweekly-contest-189/problems/elevator-requests-i/submissions/2107970299/) |

## Solution

```unknown
1class Solution {
2public:
3    int elevatorRequests(int n, vector<int>& requests) {
4        int m = requests.size();
5
6        // vector<int> prefix(m);
7        // prefix[0] = requests[0];
8
9        // for(int i=1; i<m; i++){
10        //     prefix[i]  = abs(prefix[i - 1] - requests[i]);
11        // }
12        int sum = requests[0];
13        for(int i = 1; i<m; i++){
14            sum += abs(requests[i-1] - requests[i]);
15        }
16
17        return sum;
18    }
19};
```

---
*Auto-synced by LeetCode Git Sync on 2026-08-15*