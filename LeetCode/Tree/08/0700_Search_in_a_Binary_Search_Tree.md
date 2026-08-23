# 700. Search in a Binary Search Tree

![LeetCode](https://img.shields.io/badge/LeetCode-%2523700-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Tree, Binary Search Tree, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 24, 2026 at 12:28 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/search-in-a-binary-search-tree/submissions/2117743498/) |

## Solution

```unknown
 */
class Solution {
public:
    TreeNode* searchBST(TreeNode* root, int val) {
        if(root == nullptr) return nullptr;
        if(root->val == val) return root;
        if(root->val < val){
            return searchBST(root->right, val);
        }else{
           return  searchBST(root->left, val);
        }


 * };
 *     TreeNode(int x, TreeNode *left, TreeNode *right) : val(x), left(left), right(right) {}
 *     TreeNode(int x) : val(x), left(nullptr), right(nullptr) {}
 *     TreeNode() : val(0), left(nullptr), right(nullptr) {}
 *     TreeNode *right;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-23*