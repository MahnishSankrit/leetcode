# 907. Sum of Subarray Minimums

![LeetCode](https://img.shields.io/badge/LeetCode-%2523907-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming, Stack, Monotonic Stack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 6, 2026 at 05:20 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/sum-of-subarray-minimums/submissions/2096612593/) |

## Solution

```unknown
                    right[i] = n;
                    st.push(i);
                if(st.empty()){
                }
                    st.pop();
                while(!st.empty() && arr[st.top()] > arr[i]){
            }else{
                st.push(i);
                right[i] = n;
            if(st.empty()){
        for(int i=n-1; i>= 0; i--){

        
        // vector<int> right(n);
        int n = arr.size();
        stack<int> st;
    vector<int> rightmini(vector<int> &arr, vector<int> &right){


```

---
*Auto-synced by LeetCode Git Sync on 2026-08-06*