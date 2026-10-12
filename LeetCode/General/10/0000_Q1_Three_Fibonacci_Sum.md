# . Q1. Three Fibonacci Sum

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 12, 2026 at 11:13 PM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-523/problems/three-fibonacci-sum/submissions/2170463337/) |

## Solution

```unknown
1class Solution {
2public:
3    bool solve(long long  a, long long  b, long long c, int n){
4        if(a + b + c  == n )return true;
5        if(a + b + c > n) return false;
6
7        long long next = b + c;
8
9        return solve(b ,c, next, n);
10        
11    }
12    bool threeFibonacciSum(int n) {
13        long long a = 0;
14        long long  b= 1;
15        long long c = 1;
16
17        return solve(0, 1, 1, n);
18    }
19};
```

---
*Auto-synced by LeetCode Git Sync on 2026-10-12*