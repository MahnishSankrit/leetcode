# 443. String Compression

![LeetCode](https://img.shields.io/badge/LeetCode-%2523443-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Two Pointers, String |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | November 20, 2026 at 01:08 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/string-compression/submissions/2199585439/) |

## Solution

```unknown
        for(int i=1; i<n; i++){  
            if(prev != chars[i]){
                s+=prev;
                if(count > 1) s+= to_string(count);
                count = 1;
                prev=chars[i];
            }else{
            count++;
            }
        }
        s += prev;
       if(count > 1) s+= to_string(count); 

       for(int i=0; i<s.length(); i++){
            chars[i] = s[i];
       }

```

---
*Auto-synced by LeetCode Git Sync on 2026-11-19*