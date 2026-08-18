# 257. Binary Tree Paths

![LeetCode](https://img.shields.io/badge/LeetCode-%2523257-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | String, Backtracking, Tree, Depth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 18, 2026 at 11:18 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/binary-tree-paths/submissions/2111814989/) |

## Solution

```unknown

        temp += "->";

        path(root->left, ans, temp);
        path(root->right, ans, temp);

        // temp.pop_back();
        temp.resize(len);
    }

    vector<string> binaryTreePaths(TreeNode* root) {
        vector<string> ans;
        string temp;
        path(root, ans, temp);


        return ans;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-18*