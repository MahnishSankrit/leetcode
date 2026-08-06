# 496. Next Greater Element I

![LeetCode](https://img.shields.io/badge/LeetCode-%2523496-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Hash Table, Stack, Monotonic Stack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 7, 2026 at 01:05 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/next-greater-element-i/description/) |

## Solution

```unknown
                st.push(nums2[i]);
                mp[nums2[i]] = st.top();
            }else if(st.top() > nums2[i]){
                st.push(nums2[i]);
                mp[nums2[i]] = -1;
            if(st.empty()){
        for(int i=n2-1; i>=0; i--){

        unordered_map<int, int> mp;
        stack<int> st;
        int n2 = nums2.size();
        vector<int> ans;
    vector<int> nextGreaterElement(vector<int>& nums1, vector<int>& nums2) {
        int n1= nums1.size();
public:
class Solution {

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-06*