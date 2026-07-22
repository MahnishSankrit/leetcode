# 160. Intersection of Two Linked Lists

![LeetCode](https://img.shields.io/badge/LeetCode-%2523160-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Hash Table, Linked List, Two Pointers |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 23, 2026 at 01:14 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/intersection-of-two-linked-lists/submissions/2077620930/) |

## Solution

```unknown
                curr2 = headA;
            if(curr2== nullptr){
            }else{
                curr1 = curr1->next;
            }
               
                curr1 = headB;

        while(curr1 !=  curr2){
            if(curr1== nullptr){
            }else{
                curr2 = curr2->next;

            }

        } 

        return curr1;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-22*