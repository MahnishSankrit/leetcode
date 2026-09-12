# . Q1. Count Values With Equally Spaced Occurrences I

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 12, 2026 at 10:18 PM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/biweekly-contest-191/problems/count-values-with-equally-spaced-occurrences-i/submissions/2139799118/) |

## Solution

```unknown
1class Solution {
2public:
3    int countSpecialIntegers(vector<int>& nums) {
4
5        unordered_map<int, vector<int>> mp;
6
7        // Store indices of every number
8        for(int i = 0; i < nums.size(); i++) {
9            mp[nums[i]].push_back(i);
10        }
11
12        int ans = 0;
13
14        for(auto it : mp) {
15
16            // Must appear exactly 3 times
17            if(it.second.size() != 3)
18                continue;
19
20            vector<int>& pos = it.second;
21
22            // Check equal spacing
23            if(pos[1] - pos[0] == pos[2] - pos[1]) {
24                ans++;
25            }
26        }
27
28        return ans;
29    }
30};
```

---
*Auto-synced by LeetCode Git Sync on 2026-09-12*