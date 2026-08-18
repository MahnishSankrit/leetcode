# 1378. Replace Employee ID With The Unique Identifier

![LeetCode](https://img.shields.io/badge/LeetCode-%25231378-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Database |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 19, 2026 at 01:32 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier/submissions/2111962109/) |

## Solution

```unknown
# Write your MySQL query statement below
select unique_id, name
from Employees
left join EmployeeUNI on Employees.id = EmployeeUNI.id;


```

---
*Auto-synced by LeetCode Git Sync on 2026-08-18*