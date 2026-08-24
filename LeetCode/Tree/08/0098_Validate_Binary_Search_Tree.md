# 98. Validate Binary Search Tree

![LeetCode](https://img.shields.io/badge/LeetCode-%252398-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Tree, Depth-First Search, Binary Search Tree, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 25, 2026 at 01:21 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/validate-binary-search-tree/) |

## Solution

```unknown

            if(root == nullptr) return true;
            vector<int> arr;
            inorder(root, arr);

            for(int i=0; i<arr.size()-1; i++){
                if(arr[i] >= arr[i+1]) return false;
            }

            return true;
        }
    };

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-24*