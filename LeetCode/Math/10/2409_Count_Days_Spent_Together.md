# 2409. Count Days Spent Together

![LeetCode](https://img.shields.io/badge/LeetCode-%25232409-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Math, String |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 24, 2026 at 07:11 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/count-days-spent-together/submissions/2180464037/) |

## Solution

```unknown
        int AliceArrive = stringToInt(arriveAlice);
        int AliceLeave = stringToInt(leaveAlice);
        int BobArrive = stringToInt(arriveBob);
        int BobLeave = stringToInt(leaveBob);

        int val1 = max(AliceArrive, BobArrive);
        int val2 = min(AliceLeave, BobLeave);

        return max(0, val2 - val1 + 1);
          
    }
};
        
    int countDaysTogether(string arriveAlice, string leaveAlice, string arriveBob, string leaveBob) {

```

---
*Auto-synced by LeetCode Git Sync on 2026-10-24*