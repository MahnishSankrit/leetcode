# . Q2. Find All Numbers Disappeared in an Array II

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 23, 2026 at 11:20 PM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-516/problems/find-all-numbers-disappeared-in-an-array-ii/submissions/2117666323/) |

## Solution

```unknown
1class Solution {
2public:
3    vector<vector<int>> findDisappearedNumbers(vector<int>& nums, int lower, int upper) {
4        sort(nums.begin(), nums.end());
5        int n=nums.size();
6        int j=0;
7        vector<vector<int>> ans;
8        vector<int> res;
9        for(int i=lower; i<=upper; i++){
10            
11            while (j < n && nums[j] < i) {
12            j++;
13        }
14            if(j < n && i == nums[j]){
15                j++;
16            }else{
17                res.push_back(i);
18            }
19        }
20
21        for(int i=0; i<res.size(); i++){
22            int start = res[i];
23            int end = start;
24
25            while(i + 1 <res.size()  && res[i+1] == end + 1){
26                i++;
27                end = res[i];
28            }
29
30            ans.push_back({start, end});
31        }
32
33        return ans;
34    }
35};
```

---
*Auto-synced by LeetCode Git Sync on 2026-08-23*