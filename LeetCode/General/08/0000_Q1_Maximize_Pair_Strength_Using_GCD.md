# . Q1. Maximize Pair Strength Using GCD

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 2, 2026 at 04:41 PM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-513/problems/maximize-pair-strength-using-gcd/) |

## Solution

```unknown
C++99123456789101112131415161718›⌄⌄⌄⌄class Solution {public:    long long maxPairStrength(vector<int>& nums) {        int n=nums.size();        long long  maxVal = LLONG_MIN;        for(int i=0; i<n; i++){            for(int j=i+1; j<n; j++){                long long num =1LL * nums[i] * nums[j];                long long gc = __gcd(nums[i], nums[j]);                long long val = gc * gc;                long long res = num / val;                maxVal = max(maxVal, res);            }        }        return maxVal;    }};SavedLn 1, Col 1RunSubmit
```

---
*Auto-synced by LeetCode Git Sync on 2026-08-02*