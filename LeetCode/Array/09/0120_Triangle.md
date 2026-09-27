# 120. Triangle

![LeetCode](https://img.shields.io/badge/LeetCode-%2523120-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 27, 2026 at 06:08 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/triangle/) |

## Solution

```unknown
        vector<vector<int>> dp(m, vector<int>(m, 0));
    

        for(int i=m-1; i>=0; i--){
            dp[m-1][i] = triangle[m-1][i];
        }

        for(int i=m-2;i>=0; i--){
            for(int j=i; j>=0; j--){

                int left = triangle[i][j] + dp[i+1][j];
                int right = triangle[i][j] + dp[i+1][j+1];

                dp[i][j] = min(left, right);

            }
        }

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-27*