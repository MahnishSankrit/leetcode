# 182. Duplicate Emails

![LeetCode](https://img.shields.io/badge/LeetCode-%2523182-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Database |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 13, 2026 at 10:48 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/duplicate-emails/submissions/2140844684/) |

## Solution

```unknown
# Write your MySQL query statement below
SELECT email
FROM Person
GROUP BY email
HAVING COUNT(email) > 1;

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-13*