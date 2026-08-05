# 42. Trapping Rain Water

![LeetCode](https://img.shields.io/badge/LeetCode-%252342-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-red) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Hard |
| **Topics** | Array, Two Pointers, Dynamic Programming, Stack, Monotonic Stack |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 5, 2026 at 10:29 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/trapping-rain-water/submissions/2095637526/) |

## Solution

```unknown
        right[n-1] = height[n-1];
        vector<int> right(n);
    vector<int> rightmax(vector<int> &height, int &n){

        
        for(int i=n-2; i>=0; i--){
            right[i] = max(right[i+1], height[i]);
        }

        return right;
    }

    int trap(vector<int>& height) {
        int n=height.size();

        vector<int> left = leftmax(height, n);
        vector<int> right = rightmax(height, n);

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-05*