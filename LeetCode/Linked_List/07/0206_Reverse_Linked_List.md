# 206. Reverse Linked List

![LeetCode](https://img.shields.io/badge/LeetCode-%2523206-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Linked List, Recursion |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 18, 2026 at 01:48 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/reverse-linked-list/submissions/2071558600/) |

## Solution

```unknown
public:
    ListNode* reverseList(ListNode* head) {
        if(!head) return nullptr;

        ListNode *curr = head;

        ListNode *prev = nullptr;

        return prev;
class Solution {
 */
        while(curr != nullptr){
            ListNode *future = curr->next;
        }
    }
            curr->next = prev;
            prev = curr;
            curr = future;

};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-17*