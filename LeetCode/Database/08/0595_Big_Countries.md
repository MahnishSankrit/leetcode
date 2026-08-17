# 595. Big Countries

![LeetCode](https://img.shields.io/badge/LeetCode-%2523595-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Database |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 17, 2026 at 07:30 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/big-countries/) |

## Solution

```unknown
# Write your MySQL query statement below

select name, population, area
from World
where area >= 3000000 or population  >= 25000000;



```

---
*Auto-synced by LeetCode Git Sync on 2026-08-17*