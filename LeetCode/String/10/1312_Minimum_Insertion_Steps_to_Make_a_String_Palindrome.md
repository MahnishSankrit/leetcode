# 1312. Minimum Insertion Steps to Make a String Palindrome

![LeetCode](https://img.shields.io/badge/LeetCode-%25231312-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-red) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Hard |
| **Topics** | String, Dynamic Programming |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 22, 2026 at 12:13 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/minimum-insertion-steps-to-make-a-string-palindrome/submissions/2178270858/) |

## Solution

```unknown
                }else{
                    skip1 = dp[i][j-1];
                    take = 2 + dp[i+1][j-1];
                }else if(s[i] == s[j]){
                    skip2 = dp[i+1][j];
                }
                    dp[i][j] = 1;

                dp[i][j] = max(take, max(skip1, skip2));
            }
        }

                if(i == j) {
                int take =0, skip1= 0, skip2=0;
            for(int j=i; j<n; j++){
        for(int i=n-1; i>=0; i--){
                    continue;

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-21*