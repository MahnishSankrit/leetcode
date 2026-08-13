# 102. Binary Tree Level Order Traversal

![LeetCode](https://img.shields.io/badge/LeetCode-%2523102-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Tree, Breadth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 13, 2026 at 09:04 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/binary-tree-level-order-traversal/submissions/2105609354/) |

## Solution

```unknown
                q.pop();
        while(!q.empty()){
            int size = q.size();
            vector<int> arr;
            for(int i=0; i<size; i++){
                TreeNode *data = q.front();

        q.push(root);
       
        queue<TreeNode*> q;

                arr.push_back(data->val);
                if(data->left != nullptr){
                    q.push(data->left);
                }
                if(data->right != nullptr){
                    q.push(data->right);

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-13*