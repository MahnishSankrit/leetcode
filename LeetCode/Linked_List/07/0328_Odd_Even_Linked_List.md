# 328. Odd Even Linked List

![LeetCode](https://img.shields.io/badge/LeetCode-%2523328-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | Linked List |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | July 19, 2026 at 02:55 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/odd-even-linked-list/submissions/2072749985/) |

## Solution

```unknown
                    tail1 = tail1->next;
                }
            }else{
                if(curr2 == nullptr){
                    curr2 = newNode;
                    tail2 = newNode;
                }else{
                tail2->next = newNode;
                tail2 = tail2->next;
                }
            }   
            temp = temp->next;
        }

        tail1->next = curr2;
        return curr1;
        
    }
};

```

---
*Auto-synced by LeetCode Git Sync on 2026-07-18*