# 3754. Concatenate Non-Zero Digits and Multiply by Sum I

![LeetCode](https://img.shields.io/badge/LeetCode-%25233754-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Math |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 7, 2026 at 02:21 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/concatenate-non-zero-digits-and-multiply-by-sum-i/) |

## Solution

```unknown
        while(n > 0){
            digit.push_back(n % 10);
            n /= 10;
        }

        for(int i=digit.size()-1; i>=0; i--){
            if(digit[i] != 0){
                sum += digit[i];
                num = num * 10 + digit[i];
            }
        }
        
        return num* sum;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-07*