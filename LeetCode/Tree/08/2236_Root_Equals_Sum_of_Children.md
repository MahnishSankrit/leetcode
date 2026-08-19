# 2236. Root Equals Sum of Children

![LeetCode](https://img.shields.io/badge/LeetCode-%25232236-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Tree, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 20, 2026 at 01:10 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/root-equals-sum-of-children/submissions/2113188672/) |

## Solution

```unknown
 */
class Solution {
public:
    bool checkTree(TreeNode* root) {
        if(root == nullptr) return true;
        if(root->left == nullptr && root->right == nullptr) return true;

        if(root->left == nullptr){
            if(root->val != root->right->val) return false;
        }else if(root->right == nullptr){
            if(root->val != root->left->val) return false;
        }else{
            if(root->val != root->left->val + root->right->val) return false;
        }
    }

        return checkTree(root->left) && checkTree(root->right);

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-19*