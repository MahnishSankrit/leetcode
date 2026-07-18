# 234. Palindrome Linked List

![LeetCode](https://img.shields.io/badge/LeetCode-%2523234-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Linked List, Two Pointers, Stack, Recursion |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 19, 2026 at 12:17 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/palindrome-linked-list/) |

## Solution

```unknown
            fast = fast->next->next;
        }

        slow = rev(slow);

        while(slow){
            if(temp->val != slow->val) return false;

            temp = temp->next;
            slow = slow->next;
        }

    
        
        return true;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-18*