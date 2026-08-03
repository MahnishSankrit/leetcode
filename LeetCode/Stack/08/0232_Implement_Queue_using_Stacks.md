# 232. Implement Queue using Stacks

![LeetCode](https://img.shields.io/badge/LeetCode-%2523232-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Stack, Design, Queue |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 4, 2026 at 12:29 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/implement-queue-using-stacks/submissions/2093126105/) |

## Solution

```unknown
    }
        return val;
        
        if(empty()) return -1;
    int pop() {
    
    }
        while(!st1.empty()){
            st2.push(st1.top());
        }
            st1.pop();
        int val = st2.top();
        st2.pop();
        while(!st2.empty()){
            st1.push(st2.top());
        }
            st2.pop();

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-03*