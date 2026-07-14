# 1903. Largest Odd Number in String

![LeetCode](https://img.shields.io/badge/LeetCode-%25231903-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Math, String, Greedy |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 14, 2026 at 03:57 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/largest-odd-number-in-string/submissions/2067236031/) |

## Solution

```unknown
class Solution {
public:
    string largestOddNumber(string num) {
        // if(stoi(num) % 2 != 0) return num;
        int n=num.length();
        int maxVal = INT_MIN;
        string res = "";
        int  idx = -1;
        for(int i=n-1; i>=0; i--){
            if((num[i] - '0') % 2 != 0){
               idx = i;
               break;
            }
        }
        if(idx == -1) return res;
 
        for(int i=0; i<=idx; i++){
            res += num[i];
        }


```

---
*Auto-synced by LeetCode Git Sync on 2026-07-14*