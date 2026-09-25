# 931. Minimum Falling Path Sum

![LeetCode](https://img.shields.io/badge/LeetCode-%2523931-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Dynamic Programming, Matrix |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 25, 2026 at 06:06 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-falling-path-sum/) |

## Solution

```unknown
        int m=matrix.size();
        int n=matrix[0].size();
    int minFallingPathSum(vector<vector<int>>& matrix) {
    }
        return min(down, min(left, right));

        int  down = matrix[i][j] + solve(m, n, i+1, j, matrix);
        int  right = matrix[i][j] + solve(m, n, i+1, j+1, matrix);
        int left = matrix[i][j] + solve(m, n, i+1, j-1, matrix);

        if(i == m-1) return matrix[i][j];
        if(j < 0 || j >= n) return 900;
    int solve(int m, int n, int i, int j, vector<vector<int>> &matrix){
public:
class Solution {
 // this isthe recursion way which gives tle

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-25*