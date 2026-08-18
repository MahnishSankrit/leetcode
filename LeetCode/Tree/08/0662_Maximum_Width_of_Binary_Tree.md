# 662. Maximum Width of Binary Tree

![LeetCode](https://img.shields.io/badge/LeetCode-%2523662-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Tree, Depth-First Search, Breadth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 19, 2026 at 01:27 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/maximum-width-of-binary-tree/submissions/2111958783/) |

## Solution

```unknown

          for(long long i=0; i<size; i++){
            TreeNode *temp = q.front().first;
            long long index = q.front().second;
            q.pop();
            last = index;
            index = index - first;

            if(temp->left != nullptr){
                q.push({temp->left, 2 * index + 1});
            }
            if(temp->right != nullptr){
                q.push({temp->right, 2 * index  + 2});
            }
            long long  width = last - first  + 1;
            val = max(val, (int)width);
          }

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-18*