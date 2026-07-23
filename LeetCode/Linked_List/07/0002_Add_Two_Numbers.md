# 2. Add Two Numbers

![LeetCode](https://img.shields.io/badge/LeetCode-%25232-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Linked List, Math, Recursion |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 23, 2026 at 07:22 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/add-two-numbers/) |

## Solution

```unknown

    //     while(curr != nullptr){
    //         ListNode *temp = curr->next;
    //         curr->next = prev;
    //         prev = curr
    //         curr = temp;
    //     }

    //     return prev;
    // }
    ListNode* addTwoNumbers(ListNode* l1, ListNode* l2) {
        if(l1 == nullptr) return l2;
        if(l2 == nullptr) return l1;

        ListNode *dummy = new ListNode(0);
        ListNode *temp = dummy;
        int carry = 0;
        while(l1 != nullptr || l2 != nullptr || carry){
            int sum =carry;


```

---
*Auto-synced by LeetCode Git Sync on 2026-07-23*