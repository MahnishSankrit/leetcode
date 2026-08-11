# 424. Longest Repeating Character Replacement

![LeetCode](https://img.shields.io/badge/LeetCode-%2523424-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Hash Table, String, Sliding Window |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 11, 2026 at 03:40 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/longest-repeating-character-replacement/submissions/2102670998/) |

## Solution

```unknown

            int change = window - maxFreq;
            
                while(change > k){
                    mp[s[j]]--;
                    j++;
                }
                window = i - j + 1;

            maxWindow = max(maxWindow , window);
        }
            int window = i -j +1;
            maxFreq = max(maxFreq, mp[s[i]]);

            mp[s[i]]++;
                    change = window - maxFreq;
                    window = i - j  + 1;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-11*