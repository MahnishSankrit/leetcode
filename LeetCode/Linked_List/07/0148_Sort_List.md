# 148. Sort List

![LeetCode](https://img.shields.io/badge/LeetCode-%2523148-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Linked List, Two Pointers, Divide and Conquer, Sorting, Merge Sort |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 22, 2026 at 01:20 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/sort-list/) |

## Solution

```unknown
            for (int j = 0; j < n - 1 - i; j++) {
                    ListNode* temp = curr->next;
                    curr->next = temp->next;
                    temp->next = curr;
                    }
                if (curr->val > curr->next->val) {
                    prev = temp;
        for (int i = 0; i < n-1; i++) {
            prev = nullptr;
                    if (prev == nullptr) {
                        head = temp;
                    } else {
                        prev->next = temp;

        ListNode* prev = nullptr;
        curr = head;
        }
            curr = curr->next;
            n++;
            curr = head;

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-22*