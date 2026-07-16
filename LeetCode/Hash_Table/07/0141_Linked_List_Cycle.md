# 141. Linked List Cycle

![LeetCode](https://img.shields.io/badge/LeetCode-%2523141-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Hash Table, Linked List, Two Pointers |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 17, 2026 at 01:15 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/linked-list-cycle/submissions/2070368798/) |

## Solution

```unknown
 * struct ListNode {
 *     int val;
 *     ListNode *next;
 *     ListNode(int x) : val(x), next(NULL) {}
 * };
 */
class Solution {
public:
    bool hasCycle(ListNode *head) {
        ListNode *slow = head;
        ListNode *fast = head;

        while(fast != nullptr && fast->next != nullptr){
            slow = slow->next;
        } 

        return false;
            fast = fast->next->next;
            if(slow == fast) return true;
    }

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-16*