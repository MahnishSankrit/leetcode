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
| **Submitted** | August 5, 2026 at 12:28 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/next-greater-element-i/submissions/2094508122/) |

## Solution

```unknown
            }else if(st.top() > nums2[i]){
                mp[nums2[i]] = st.top();
                st.push(nums2[i]);
                st.push(nums2[i]);
                mp[nums2[i]] = -1;
        for(int i=n2-1; i>=0; i--){
            if(st.empty()){
            }else if(st.top() < nums2[i]){
                while(!st.empty() && st.top() <= nums2[i]){
                    st.pop();
                }
                if(st.empty()){
                    mp[nums2[i]] = -1;
                    st.push(nums2[i]);
                }else{
                    mp[nums2[i]] = st.top();
                }
                st.push(nums2[i]);

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-04*