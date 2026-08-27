# 1280. Students and Examinations

![LeetCode](https://img.shields.io/badge/LeetCode-%25231280-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Database |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 28, 2026 at 02:30 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/students-and-examinations/submissions/2122361985/) |

## Solution

```unknown
# Write your MySQL query statement below
select s.student_id, s.student_name, d.subject_name, count(e.subject_name) as attended_exams
from Students s
cross join Subjects d 
group by s.student_id, s.student_name, d.subject_name


order by s.student_id, d.subject_name
left join Examinations e on s.student_id = e.student_id
and  d.subject_name = e.subject_name


```

---
*Auto-synced by LeetCode Git Sync on 2026-08-27*