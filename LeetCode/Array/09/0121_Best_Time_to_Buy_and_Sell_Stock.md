# 121. Best Time to Buy and Sell Stock

![LeetCode](https://img.shields.io/badge/LeetCode-%2523121-FFA116) ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Unknown-blue) ![Runtime](https://img.shields.io/badge/Runtime-N%2FA-success) ![Memory](https://img.shields.io/badge/Memory-N%2FA-informational)

## Problem Info

| Property | Value |
| --- | --- |
| **Difficulty** | Easy |
| **Topics** | Array, Dynamic Programming |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Submitted** | September 24, 2026 at 07:49 PM |
| **Link** | [View on LeetCode](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/submissions/2152063623/) |

## Solution

```unknown
class Solution {
public:
    int maxProfit(vector<int>& prices) {
        int n = prices.size();
        int buy = prices[0];
        for(int i=1; i<n; i++){
            if(prices[i] > buy){
        }
                maxProfit = max(maxProfit, prices[i] - buy);
            }else{
        int maxProfit = 0;
                buy = prices[i];
            }
    }

        return maxProfit;

```

---
*Auto-synced by LeetCode Git Sync on 2026-09-24*