# 105. Construct Binary Tree from Preorder and Inorder Traversal

![LeetCode](https://img.shields.io/badge/LeetCode-%2523105-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Hash Table, Divide and Conquer, Tree, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 21, 2026 at 09:06 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/submissions/2115209330/) |

## Solution

```unknown
        int numleft = inroot - instart;
        int inroot = mp[root->val];
        TreeNode *root = new TreeNode(preorder[prestart]);

        if(prestart > preend || instart > inend) return nullptr ;
    inend, map<int, int> &mp){

        root->left = construct(preorder, prestart + 1, prestart + numleft,
                           inorder, instart, inroot - 1, mp);
        root->right = construct(preorder, prestart + numleft + 1, preend,
                            inorder, inroot + 1, inend, mp);
    }

    TreeNode* buildTree(vector<int>& preorder, vector<int>& inorder) {
        map<int, int> mp;
                            
        return root;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-21*