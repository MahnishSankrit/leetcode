# 653. Two Sum IV - Input is a BST

![LeetCode](https://img.shields.io/badge/LeetCode-%2523653-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Hash Table, Two Pointers, Tree, Depth-First Search, Breadth-First Search, Binary Search Tree, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 26, 2026 at 01:27 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/submissions/2120131038/) |

## Solution

```unknown

        inorder(root, arr);
        int n= arr.size();
  
        for(int i=0; i<n; i++){
             int need = k - arr[i];

            if(mp.find(need) != mp.end()) return true;

            mp[arr[i]]++;
        }

        return false;

    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-25*