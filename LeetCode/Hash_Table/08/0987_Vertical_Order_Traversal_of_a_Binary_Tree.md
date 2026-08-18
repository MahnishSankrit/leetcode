# 987. Vertical Order Traversal of a Binary Tree

![LeetCode](https://img.shields.io/badge/LeetCode-%2523987-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Hard-red) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Hard |
| **Topics** | Hash Table, Tree, Depth-First Search, Breadth-First Search, Sorting, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 18, 2026 at 04:20 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) |

## Solution

```unknown
            auto temp  = q.front();
            q.pop();

            TreeNode *node = temp.first;
            int row = temp.second.first;
            int col = temp.second.second;

            mp[col][row].insert(node->val);
            if(node->left){
                q.push({node->left, {row+1, col - 1}});
            }

            if(node->right){
                q.push({node->right, {row+1, col+1}});
            }
        }

        vector<vector<int>> ans;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-18*