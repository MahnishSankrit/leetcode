# 863. All Nodes Distance K in Binary Tree

![LeetCode](https://img.shields.io/badge/LeetCode-%2523863-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Hash Table, Tree, Depth-First Search, Breadth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 20, 2026 at 02:39 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/) |

## Solution

```unknown
                    visited.insert(temp->right);
                }
                
                if(parent.find(temp) != parent.end() && !visited.count(parent[temp])){
                    q.push(parent[temp]);
                    visited.insert(parent[temp]);
                }
                
            }
            k--;
        }

        while(!q.empty()){

            int val = q.front()->val;
            q.pop();
            arr.push_back(val);
        }

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-19*