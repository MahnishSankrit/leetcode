# 104. Maximum Depth of Binary Tree

![LeetCode](https://img.shields.io/badge/LeetCode-%2523104-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Tree, Depth-First Search, Breadth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 15, 2026 at 12:04 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/maximum-depth-of-binary-tree/submissions/2106960801/) |

## Solution

```unknown
                    q.push(temp->left);
                }
                if(temp->right != nullptr){
                    q.push(temp->right);
                }

            }
                count++;
        }
        
        return count;
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-14*