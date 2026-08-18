# 1581. Customer Who Visited but Did Not Make Any Transactions

![LeetCode](https://img.shields.io/badge/LeetCode-%25231581-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Database |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | August 19, 2026 at 01:55 AM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/customer-who-visited-but-did-not-make-any-transactions/submissions/2111976732/) |

## Solution

```unknown
# Write your MySQL query statement below
select customer_id, count(*) as count_no_trans
from Visits
left join Transactions on Visits.visit_id = Transactions.visit_id
where transaction_id is null
group by customer_id; 


```

---
*Auto-synced by LeetCode Git Sync on 2026-08-18*