# 230. Kth Smallest Element in a BST

![LeetCode](https://img.shields.io/badge/LeetCode-%2523230-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Tree, Depth-First Search, Binary Search Tree, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 25, 2026 at 01:10 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/kth-smallest-element-in-a-bst/submissions/2118913660/) |

## Solution

```unknown

        inorder(root->left , arr);
        arr.push_back(root->val);
        inorder(root->right, arr);
    }
    int kthSmallest(TreeNode* root, int k) {
        if(root == nullptr) return -1;
        vector<int> arr;
        inorder(root, arr);

        return arr[k-1];
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-24*