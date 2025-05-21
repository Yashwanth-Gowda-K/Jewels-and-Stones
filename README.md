# Jewels-and-Stones

## Problem Statement
Given two strings `jewels` and `stones`, return how many characters in `stones` are also present in `jewels`.  
**Note:** Letters are case-sensitive (`"a"` ≠ `"A"`).

### Example:
- **Input:** `jewels = "aA"`, `stones = "aAAbbbb"`  
- **Output:** `3` *(stones `'a'`, `'A'`, `'A'` are jewels)*

## Solutions
### 1. Hash Set Approach (Optimal)
- **Time Complexity:** O(n + m) *(n = jewels length, m = stones length)*  
- **Space Complexity:** O(n) *(for storing jewels in a set)*  
