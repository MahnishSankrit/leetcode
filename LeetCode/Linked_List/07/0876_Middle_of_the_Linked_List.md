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
| **Submitted** | July 17, 2026 at 01:02 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/middle-of-the-linked-list/submissions/2070359865/) |

## Solution

```unknown
            curr = curr->next;
        while(curr != nullptr){
            count++;
        }

        int k =0;
        curr = head;
        while(k != count/2){
            curr = curr->next;
        }
        

            k++;

        ListNode * curr = head;
        int count = 0;
    ListNode* middleNode(ListNode* head) {
public:
class Solution {
 */

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-16*