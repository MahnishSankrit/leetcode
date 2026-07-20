# 2095. Delete the Middle Node of a Linked List

![LeetCode](https://img.shields.io/badge/LeetCode-%25232095-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Linked List, Two Pointers |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 20, 2026 at 07:19 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/) |

## Solution

```unknown

        ListNode *slow = head;
        ListNode *fast = head;

        ListNode *prev = nullptr;
        while(fast != nullptr && fast->next != nullptr){
            prev = slow;
            slow = slow->next;
            fast = fast->next->next;
        }

        prev->next = slow->next;

        slow->next = nullptr;
        if(head->next == nullptr) return nullptr;
        delete slow;
        return head;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-20*