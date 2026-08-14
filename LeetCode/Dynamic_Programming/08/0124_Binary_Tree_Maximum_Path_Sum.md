# 124. Binary Tree Maximum Path Sum

![LeetCode](https://img.shields.io/badge/LeetCode-%2523124-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-red) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Hard |
| **Topics** | Dynamic Programming, Tree, Depth-First Search, Binary Tree, DP on Trees |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 15, 2026 at 01:58 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/binary-tree-maximum-path-sum/submissions/2107041118/) |

## Solution

```unknown
        maxSum = max(maxSum, left + right + root->val);

        return root->val + max(left, right);

        int   right = max(0,sumPath(root->right));
        int  left = max(0, sumPath(root->left));

        if(root == nullptr) return 0;
    int sumPath(TreeNode *root){
    }
    int maxPathSum(TreeNode* root) {
        if(root == nullptr) return 0;
        // if(root->left == nullptr && root->right == nullptr) return root->val;

        sumPath(root);
        return maxSum ;
    }

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-14*