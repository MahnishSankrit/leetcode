# 584. Find Customer Referee

![LeetCode](https://img.shields.io/badge/LeetCode-%2523584-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Database |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 17, 2026 at 07:26 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/find-customer-referee/submissions/2110202001/) |

## Solution

```unknown
# Write your MySQL query statement below
select name
from Customer
where referee_id IS NULL OR referee_id != 2;

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-17*