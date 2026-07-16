# 876. Middle of the Linked List

![LeetCode](https://img.shields.io/badge/LeetCode-%2523876-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Linked List, Two Pointers |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 17, 2026 at 01:09 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/middle-of-the-linked-list/submissions/2070365006/) |

## Solution

```unknown
        ListNode *slow = head;
        int count = 0;
    ListNode* middleNode(ListNode* head) {
public:
class Solution {
 */
 * };
 *     ListNode(int x, ListNode *next) : val(x), next(next) {}
        ListNode *fast = head;

        while(fast != nullptr && fast->next != nullptr){
            slow = slow->next;
 *     ListNode(int x) : val(x), next(nullptr) {}
 *     ListNode() : val(0), next(nullptr) {}
 *     ListNode *next;
 *     int val;
            fast = fast->next->next;
            
        }


```

---
*Auto-synced by LeetCode Git Sync on 2026-07-16*