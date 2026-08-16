# 103. Binary Tree Zigzag Level Order Traversal

![LeetCode](https://img.shields.io/badge/LeetCode-%2523103-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Tree, Breadth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 16, 2026 at 10:01 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/submissions/2109219434/) |

## Solution

```unknown

        }
    }
    vector<vector<int>> zigzagLevelOrder(TreeNode* root) {
        vector<vector<int>> ans;
            }   
                }
                    q.push(temp->right);
            if(level % 2 != 0){
                reverse(arr.begin(), arr.end());
                ans.push_back(arr);
            }else{
                ans.push_back(arr);
            }

            level++;
        bfs(root, ans);

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-16*