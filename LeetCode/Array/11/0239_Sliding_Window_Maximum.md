# 239. Sliding Window Maximum

![LeetCode](https://img.shields.io/badge/LeetCode-%2523239-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-red) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Hard |
| **Topics** | Array, Queue, Sliding Window, Heap (Priority Queue), Monotonic Queue, Range Minimum/Maximum Query |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 14, 2026 at 04:47 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/sliding-window-maximum/submissions/2195592064/) |

## Solution

```unknown
            while(!dq.empty() && nums[i] >= nums[dq.back()]){
                dq.pop_back();
            }

            dq.push_back(i);
            }
                dq.pop_front();
        for(int i=0; i<n; i++){
            while(!dq.empty() && dq.front() == i-k){

        vector<int> ans;
        deque<int> dq;
    vector<int> maxSlidingWindow(vector<int>& nums, int k) {
        int n=nums.size();
public:
class Solution {

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-13*