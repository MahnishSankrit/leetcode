# 1277. Count Square Submatrices with All Ones

![LeetCode](https://img.shields.io/badge/LeetCode-%25231277-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 29, 2026 at 01:21 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/count-square-submatrices-with-all-ones/submissions/2156418866/) |

## Solution

```unknown
        
        for(int i=1; i<m; i++){
            for(int j=1; j<n; j++){
                solve(matrix, grid, m, n, i, j);
            }
        }

        }
            grid[0][i] = matrix[0][i];
        for(int i=0; i<n; i++){
        }
            grid[i][0] = matrix[i][0];
        for(int i=0; i<m; i++){
        vector<vector<int>> grid(m, vector<int>(n, -1));
        int n=matrix[0].size();
        int m=matrix.size();
    int countSquares(vector<vector<int>>& matrix) {

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-28*