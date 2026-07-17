# 142. Linked List Cycle II

![LeetCode](https://img.shields.io/badge/LeetCode-%2523142-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Hash Table, Linked List, Two Pointers |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 18, 2026 at 02:19 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/linked-list-cycle-ii/submissions/2071572408/) |

## Solution

```unknown
        while(fast != nullptr && fast->next != nullptr){
            slow = slow->next;
            fast = fast->next->next;



        ListNode *fast = head;
        if(!head) return nullptr;
        ListNode *slow = head;
    ListNode *detectCycle(ListNode *head) {
            if(slow == fast) break;
        }
        if(fast == nullptr || fast->next == nullptr) return nullptr;
        ListNode *temp = head;
        while(temp != slow && slow != nullptr){
            temp = temp->next;
            slow = slow->next;
        }
       
        return temp;

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-17*