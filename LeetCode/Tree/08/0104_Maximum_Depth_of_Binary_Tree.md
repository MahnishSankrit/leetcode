# 104. Maximum Depth of Binary Tree

![LeetCode](https://img.shields.io/badge/LeetCode-%2523104-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Tree, Depth-First Search, Breadth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 14, 2026 at 04:23 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/maximum-depth-of-binary-tree/submissions/2106506158/) |

## Solution

```unknown
        int r = height(root->right);

        return 1 +  max(l , r);
    }
    int maxDepth(TreeNode* root) {
        if(root == nullptr) return 0;

        int count = 0;
        int l = height(root->left);
    
        return height(root);
        

        if(root == nullptr) return 0;
public:
class Solution {
    int height(TreeNode *root){

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-14*