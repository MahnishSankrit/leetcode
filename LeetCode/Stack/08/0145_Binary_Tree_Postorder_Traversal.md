# 145. Binary Tree Postorder Traversal

![LeetCode](https://img.shields.io/badge/LeetCode-%2523145-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Stack, Tree, Depth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 13, 2026 at 08:08 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/binary-tree-postorder-traversal/submissions/2105545189/) |

## Solution

```unknown
public:
    void postorder(TreeNode *root, vector<int> &arr){
        if(root != nullptr){
    }
            postorder(root->left, arr);
        }
            postorder(root->right, arr);
            arr.push_back(root->val);
    vector<int> postorderTraversal(TreeNode* root) {
        vector<int> arr;
    }
        postorder(root, arr);

        return arr;
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-13*