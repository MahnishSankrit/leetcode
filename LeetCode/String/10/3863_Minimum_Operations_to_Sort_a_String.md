# 3863. Minimum Operations to Sort a String

![LeetCode](https://img.shields.io/badge/LeetCode-%25233863-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 21, 2026 at 05:34 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-operations-to-sort-a-string/submissions/2177910405/) |

## Solution

```unknown
        if(s[n-1] == max_el) return 1;

        // check if the min and max are in the middle or not as this case will take 3 steps;

        if(s[0] == min_el) return 1;

        char max_el = *max_element(s.begin(), s.end());
        char min_el = *min_element(s.begin(), s.end());

        if(is_sorted(s.begin(), s.end())) return 0;
        int n=s.length();
    int minOperations(string s) {
public:
class Solution {
        if(n == 2) return  -1;
        char min_mid = *min_element(s.begin() + 1, s.end()-1);

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-21*