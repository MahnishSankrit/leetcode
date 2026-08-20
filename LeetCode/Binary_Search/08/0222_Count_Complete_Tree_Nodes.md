# 222. Count Complete Tree Nodes

![LeetCode](https://img.shields.io/badge/LeetCode-%2523222-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Binary Search, Bit Manipulation, Tree, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 21, 2026 at 12:00 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/count-complete-tree-nodes/submissions/2114338897/) |

## Solution

```unknown
    }
    int countNodes(TreeNode* root) {
        if(root == nullptr) return 0;
        int left = getLeft(root);
        int right = getright(root);

        if(left == right){
            return pow(2, left) - 1;
        }
        return 1 + countNodes(root->left) + countNodes(root->right);
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-20*