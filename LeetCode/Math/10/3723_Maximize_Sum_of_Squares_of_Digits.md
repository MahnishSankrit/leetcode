# 3723. Maximize Sum of Squares of Digits

![LeetCode](https://img.shields.io/badge/LeetCode-%25233723-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Math, Greedy |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 14, 2026 at 08:25 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/maximize-sum-of-squares-of-digits/submissions/2172229068/) |

## Solution

```unknown
        while(num > 0){
            if(sum >= 9){
            }else{
        if(sum > 9 * num) return "";
                ans += '9';
                sum -= 9;
                ans += char('0' + sum);
            }
                sum = 0;
            num--;
    string maxSumOfSquares(int num, int sum) {
public:
class Solution {
        string ans = "";
        if(sum == 0) return "";
        }

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-14*