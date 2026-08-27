# 577. Employee Bonus

![LeetCode](https://img.shields.io/badge/LeetCode-%2523577-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Database |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 28, 2026 at 02:10 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/employee-bonus/submissions/2122352635/) |

## Solution

```unknown
# Write your MySQL query statement below
select name, bonus
from Employee e
left Join Bonus b on e.empId = b.empId
-- group by name
-- having bonus < 1000 or bonus is null
where bonus < 1000 or bonus is null



```

---
*Auto-synced by LeetCode Git Sync on 2026-08-27*