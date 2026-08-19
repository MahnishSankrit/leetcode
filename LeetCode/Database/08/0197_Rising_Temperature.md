# 197. Rising Temperature

![LeetCode](https://img.shields.io/badge/LeetCode-%2523197-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Database |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 19, 2026 at 03:26 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/rising-temperature/submissions/2112529843/) |

## Solution

```unknown
# Write your MySQL query statement below

select w1.id
from Weather w1
join Weather w2
on datediff(w1.recordDate , w2.recordDate) = 1



and w1.temperature > w2.temperature;


```

---
*Auto-synced by LeetCode Git Sync on 2026-08-19*