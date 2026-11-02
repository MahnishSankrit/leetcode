# . Q1. Minimum Value of Merged Integers

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 3, 2026 at 02:37 AM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-526/problems/minimum-value-of-merged-integers/description/) |

## Solution

```unknown
1class Solution {
2public:
3    int minMergedInteger(vector<int>& nums) {
4        vector<string> temp;
5        int n=nums.size();
6
7        for(int i=1; i<n; i++){
8            if(i % 2 == 0) continue;
9            string s1 = to_string(nums[i-1]);
10            string s2 = to_string(nums[i]);
11
12            string t = s1 + s2;
13            temp.push_back(t);
14        }
15
16        int minVal= INT_MAX;
17        for(int i=0; i<temp.size(); i++){
18            // if(i % 2 == 0) continue;
19            int val = stoi(temp[i]);
20            minVal = min(minVal, val);
21        }
22
23        return minVal;
24    }
25};
```

---
*Auto-synced by LeetCode Git Sync on 2026-11-02*