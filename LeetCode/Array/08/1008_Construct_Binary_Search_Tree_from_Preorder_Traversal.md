# 1008. Construct Binary Search Tree from Preorder Traversal

![LeetCode](https://img.shields.io/badge/LeetCode-%25231008-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Array, Stack, Tree, Binary Search Tree, Monotonic Stack, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 25, 2026 at 10:46 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/submissions/2119954317/) |

## Solution

```unknown
                curr->right = temp;
                TreeNode *temp = new TreeNode(preorder[i]);
            if(curr->right == nullptr){
        }else {
            }
                constBST(preorder, root ,curr->left, i);
            }else{
                constBST(preorder,root,  root, i+1);
                curr->left = temp;
                TreeNode *temp = new TreeNode(preorder[i]);
            if(curr->left == nullptr){
        if(curr->val > preorder[i]){
        // TreeNode *curr = root;

        if(i == preorder.size()) return;
    void constBST(vector<int> &preorder, TreeNode *root, TreeNode *curr , int i){
public:

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-25*