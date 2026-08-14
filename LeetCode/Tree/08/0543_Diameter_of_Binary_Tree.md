# 543. Diameter of Binary Tree

![LeetCode](https://img.shields.io/badge/LeetCode-%2523543-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Tree, Depth-First Search, Binary Tree, DP on Trees |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 15, 2026 at 01:32 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/diameter-of-binary-tree/submissions/2107026568/) |

## Solution

```unknown
        return 1 + max(lef, rig);

        int rig = height(root->right);
        int lef = height(root->left);

        if(root == nullptr) return 0;
    int height(TreeNode *root){
public:
    int maxlen = 0;
class Solution {
 */
 * };
 *     TreeNode(int x, TreeNode *left, TreeNode *right) : val(x), left(left), right(right) {}
 *     TreeNode(int x) : val(x), left(nullptr), right(nullptr) {}
 *     TreeNode() : val(0), left(nullptr), right(nullptr) {}
 *     TreeNode *right;
 *     TreeNode *left;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-14*