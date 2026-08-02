# . Q2. Count Subarrays With Even Odd Ratio I

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 2, 2026 at 05:44 PM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-513/problems/count-subarrays-with-even-odd-ratio-i/submissions/2091324939/) |

## Solution

```unknown
1class Solution {
2public:
3    int countRatioSubarrays(vector<int>& nums, int a, int b) {
4        int n = nums.size();
5        double ratio = (double)a / b;
6        int count = 0;
7
8        for(int i=0; i<n; i++){
9             double odd = 0;
10             double even = 0;
11            if(nums[i] % 2 != 0){
12                odd++;
13            }
14            else { even++; }
15            if(odd != 0){
16                double val = even/odd;
17                if(val <= ratio) count++;
18            }
19            for(int j=i+1; j<n; j++){
20                if(nums[j] % 2 != 0) odd++;
21                else even++;
22
23                if(odd == 0) continue;
24                    double rat = even / odd;
25                    if(rat <= ratio) count++;
26                    
27            }
28        }
29        return count;
30    }
31    
32};
```

---
*Auto-synced by LeetCode Git Sync on 2026-08-02*