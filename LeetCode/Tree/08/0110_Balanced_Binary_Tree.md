# 110. Balanced Binary Tree

![LeetCode](https://img.shields.io/badge/LeetCode-%2523110-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Tree, Depth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 15, 2026 at 01:04 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/balanced-binary-tree/submissions/2107008897/) |

## Solution

```unknown
        int left = 0;
        int right = 0;
        if(root->left != nullptr){
            left = height(root->left);
        }
        if(root->right != nullptr){
            right  = height(root->right);
        }

        // if(root->left == nullptr && root->right == nullptr) return true;
        if(abs(left - right) > 1)return false;

        return isBalanced(root->left) && isBalanced(root->right);
    }

};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-14*