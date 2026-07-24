# 8. String to Integer (atoi)

![LeetCode](https://img.shields.io/badge/LeetCode-%25238-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | String |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 24, 2026 at 06:38 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/string-to-integer-atoi/submissions/2079594085/) |

## Solution

```unknown
    }
        return atoiFunc(s, i+1, num, sign);

        if(sign && -num < INT_MIN) return INT_MIN;
        if(!sign && num > INT_MAX) return INT_MAX;

        
        num = num * 10 + (s[i] - '0');

        }
             return num;
            if(sign) return -num;
        if(i >= s.length() || !isdigit(s[i])){
    int atoiFunc(string &s, int i, long long num, bool sign){
public:
class Solution {
    int myAtoi(string s) {

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-24*