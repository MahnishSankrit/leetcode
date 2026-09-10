# 2265. Count Nodes Equal to Average of Subtree

![LeetCode](https://img.shields.io/badge/LeetCode-%25232265-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Tree, Depth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 10, 2026 at 11:28 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/count-nodes-equal-to-average-of-subtree/submissions/2137819454/) |

## Solution

```unknown
        return left + right + root->val;
        if(root->val == (left + right + root->val)/ node) count++;
        node = leftnode + rightnode + 1;

    }
    int averageOfSubtree(TreeNode* root) {
        if(root == nullptr) return 0;
        int count = 0;

        countNode(root, count, node);

        return count;
        
        
    }
        int node = 0;
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-10*