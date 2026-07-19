# . Q2. Count Dominant Nodes in a Binary Tree

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 19, 2026 at 11:38 AM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-511/problems/count-dominant-nodes-in-a-binary-tree/) |

## Solution

```unknown
C++9912345678910111213141516171819202122232425262728293031323334›⌄⌄⌄⌄⌄⌄/** * Definition for a binary tree node. * struct TreeNode { *     int val; *     TreeNode *left; *     TreeNode *right; *     TreeNode() : val(0), left(nullptr), right(nullptr) {} *     TreeNode(int x) : val(x), left(nullptr), right(nullptr) {} *     TreeNode(int x, TreeNode *left, TreeNode *right) : val(x), left(left), right(right) {} * }; */class Solution {public:    int maxi(TreeNode *root, int val){        if(!root) return INT_MIN;        int left = maxi(root->left, val);        int right = maxi(root->right, val);        return max(root->val, max(left ,right));    }    void inorder(TreeNode *root, int &count){        if(root != nullptr){            inorder(root->left, count);            if(maxi(root, root->val) == root->val) count++;            inorder(root->right, count);        }    }    int countDominantNodes(TreeNode* root) {        if(!root) return 0;        int count = 0;        inorder(root, count);        return count;    }};SavedLn 1, Col 1RunSubmit
```

---
*Auto-synced by LeetCode Git Sync on 2026-07-19*