# . Q2. Prime Subset Selection I

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Medium |
| **Topics** | General |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | October 12, 2026 at 11:31 PM |
| **Link** | [View on LeetCode](https://leetcode.com/contest/weekly-contest-523/problems/prime-subset-selection-i/submissions/2170484090/) |

## Solution

```unknown
1class Solution {
2public:
3    vector<int> maxPrimes(int n, int s) {
4        vector<bool> isPrime(n + 1, true);
5
6        isPrime[0] = isPrime[1] = false;
7
8        // Sieve of Eratosthenes
9        for (int i = 2; 1LL * i * i <= n; i++) {
10            if (isPrime[i]) {
11                for (int j = i * i; j <= n; j += i) {
12                    isPrime[j] = false;
13                }
14            }
15        }
16
17        vector<int> ans;
18        long long sum = 0;
19
20        for (int i = 2; i <= n; i++) {
21            if (!isPrime[i]) continue;
22
23            if (sum + i > s) break;
24
25            sum += i;
26            ans.push_back(i);
27        }
28
29        return ans;
30    }
31};
```

---
*Auto-synced by LeetCode Git Sync on 2026-10-12*