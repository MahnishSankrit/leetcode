# 144. Binary Tree Preorder Traversal

![LeetCode](https://img.shields.io/badge/LeetCode-%2523144-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Stack, Tree, Depth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 13, 2026 at 05:27 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/binary-tree-preorder-traversal/submissions/2105378323/) |

## Solution

```unknown
public:
    void preorder(TreeNode *root, vector<int> &arr){
        if(root != nullptr){
            arr.push_back(root->val);
        }
            preorder(root->left, arr);
            preorder(root->right, arr);
    }
    vector<int> preorderTraversal(TreeNode* root) {
        vector<int> arr;
    }
        preorder(root, arr);
        
        return arr;
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-13*