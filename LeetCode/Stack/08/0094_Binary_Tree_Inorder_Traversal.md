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
| **Submitted** | August 21, 2026 at 09:27 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/binary-tree-inorder-traversal/submissions/2115230426/) |

## Solution

```unknown
            }
                temp =temp->left;
                st.push(temp);
            while(temp != nullptr){

        while( temp != nullptr ||!st.empty()){
        
        TreeNode *temp = root;

        // st.push(root);
        stack<TreeNode *> st;

        if(root == nullptr) return arr;

        vector<int> arr;
    vector<int> inorderTraversal(TreeNode* root) {
  

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-21*