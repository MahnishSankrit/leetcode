# 1431. Kids With the Greatest Number of Candies

![LeetCode](https://img.shields.io/badge/LeetCode-%25231431-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 18, 2026 at 01:06 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/submissions/2198258649/) |

## Solution

```unknown
class Solution {
public:
    vector<bool> kidsWithCandies(vector<int>& candies, int extraCandies) {
        int maxi = *max_element(candies.begin(), candies.end());
        int n=candies.size();
        vector<bool> res;
        for(int i=0; i<n; i++){
            if(candies[i] + extraCandies >= maxi) res.push_back(true);
        }
    }

            else res.push_back(false);

        return res;

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-17*