# 237. Delete Node in a Linked List

![LeetCode](https://img.shields.io/badge/LeetCode-%2523237-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Linked List |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 15, 2026 at 11:19 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/delete-node-in-a-linked-list/submissions/2068976148/) |

## Solution

```unknown
 * Definition for singly-linked list.
 * struct ListNode {
 *     int val;
 *     ListNode *next;
 *     ListNode(int x) : val(x), next(NULL) {}
 * };
 */
class Solution {
public:
    void deleteNode(ListNode* node) {
       
       node->val = node->next->val;
       ListNode *temp = node->next;
    //    node = temp;
       node->next = node->next->next;  
       delete temp;  
      

    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-15*