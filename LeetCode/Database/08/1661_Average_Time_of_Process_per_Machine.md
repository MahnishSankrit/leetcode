# 1661. Average Time of Process per Machine

![LeetCode](https://img.shields.io/badge/LeetCode-%25231661-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Database |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 19, 2026 at 03:50 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/average-time-of-process-per-machine/) |

## Solution

```unknown
# Write your MySQL query statement below
select a1.machine_id, round(avg (a1.timestamp - a2.timestamp), 3)as processing_time
from Activity a1
join Activity a2
where a1.process_id =  a2.process_id
and a1.machine_id = a2.machine_id
and a1.activity_type  = "end"  and a2.activity_type = "start"
group by a1.machine_id

```

---
*Auto-synced by LeetCode Git Sync on 2026-08-19*