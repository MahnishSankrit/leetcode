# 62. Unique Paths

![LeetCode](https://img.shields.io/badge/LeetCode-%252362-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Math, Dynamic Programming, Combinatorics |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 25, 2026 at 03:46 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/unique-paths/) |

## Solution

```unknown
    }

    int uniquePaths(int m, int n) {
        // vector<vector<int>> dp(m, vector<int>(n, -1));
        vector<vector<int>> dp(m, vector<int>(n, 0));
        
        dp[0][0] = 1;
        for(int i=0; i<m; i++){
            for(int j=0; j<n; j++){
                if(i ==0 && j == 0) continue;
                else{
                    int left =0;
                    int right = 0;
                    if(i > 0) left = dp[i-1][j];
                    if(j > 0) right = dp[i][j-1];


```

---
*Auto-synced by LeetCode Git Sync on 2026-09-25*