# 1071. Greatest Common Divisor of Strings

![LeetCode](https://img.shields.io/badge/LeetCode-%25231071-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Math, String, Euclidean Algorithm, Greatest Common Divisor |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 18, 2026 at 12:57 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/greatest-common-divisor-of-strings/submissions/2198255131/) |

## Solution

```unknown
        if(str1 + str2 != str2 + str1) return "";
        int m = __gcd(n1, n2);

        int n1=str1.size();
        int n2=str2.size();

        return ans;
    string gcdOfStrings(string str1, string str2) {

        string ans = "";
        for(int i=0; i<m; i++){
            ans += str2[i];
        }
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-17*