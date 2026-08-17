# 175. Combine Two Tables

![LeetCode](https://img.shields.io/badge/LeetCode-%2523175-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Database |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 17, 2026 at 07:02 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/combine-two-tables/submissions/2110174591/) |

## Solution

```unknown
# Write your MySQL query statement below
select firstName, lastName, city, state
from Person
left join Address on Person.personId = Address.personId;



```

---
*Auto-synced by LeetCode Git Sync on 2026-08-17*