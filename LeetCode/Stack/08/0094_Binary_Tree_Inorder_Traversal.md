# 94. Binary Tree Inorder Traversal

![LeetCode](https://img.shields.io/badge/LeetCode-%252394-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Stack, Tree, Depth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 13, 2026 at 08:04 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/binary-tree-inorder-traversal/submissions/2105540946/) |

## Solution

```unknown
    void inorder(TreeNode *root, vector<int> &arr){
        if(root != nullptr){

            inorder(root->left ,arr);
        }
            arr.push_back(root->val);
            inorder(root->right, arr);
    }
    vector<int> inorderTraversal(TreeNode* root) {
        vector<int> arr;
    }
        inorder(root, arr);
public:
class Solution {
        return arr;
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-13*