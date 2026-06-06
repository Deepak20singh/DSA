# DSA
Bhai agar goal **"DP ke saare major patterns cover ho jaye"** hai, toh 40-50 questions karne ki zarurat nahi hai. Main tujhe **minimum set** de raha hoon jisse lagbhag har DP pattern touch ho jayega.

# Order Follow Karna

## Pattern 1: Fibonacci / Linear DP

### Questions

1. Climbing Stairs
2. Min Cost Climbing Stairs
3. House Robber

**Seekhega:**

```text
dp[i] = f(dp[i-1], dp[i-2])
```

---

## Pattern 2: Grid DP

### Questions

4. Unique Paths
5. Unique Paths II
6. Minimum Path Sum

**Seekhega:**

```text
dp[i][j]
```

Movement based DP.

---

## Pattern 3: Take / Not Take (0/1 Knapsack Family)

### Questions

7. 0/1 Knapsack
8. Partition Equal Subset Sum
9. Target Sum

**Most Important Pattern**

```text
Take
OR
Not Take
```

Ye samajh gaya toh aadhi DP cover.

---

## Pattern 4: Unbounded Knapsack

### Questions

10. Coin Change
11. Coin Change II

Difference:

```text
0/1 -> once
Unbounded -> infinite times
```

---

## Pattern 5: Longest Subsequence DP

### Questions

12. Longest Increasing Subsequence (LIS)
13. Largest Divisible Subset

**Seekhega:**

```text
for(j < i)
```

type transitions.

---

## Pattern 6: String DP

### Questions

14. Longest Common Subsequence (LCS)
15. Edit Distance

**Most Important String Pattern**

```text
dp[i][j]
```

based on 2 strings.

---

## Pattern 7: Palindrome DP

### Questions

16. Longest Palindromic Subsequence
17. Palindromic Substrings

Pattern:

```text
String reverse
OR
Expand intervals
```

---

## Pattern 8: Partition DP

### Questions

18. Matrix Chain Multiplication
19. Burst Balloons

Pattern:

```text
Try every partition point
```

```cpp
for(k=i;k<j;k++)
```

---

## Pattern 9: DP on Stocks

### Questions

20. Best Time to Buy and Sell Stock II
21. Best Time to Buy and Sell Stock with Cooldown

Seekhega:

```text
Buy State
Sell State
```

State machine DP.

---

## Pattern 10: DP on Subsequences + Counting

### Questions

22. Distinct Subsequences
23. Ways to Decode (Decode Ways)

Counting based DP.

---

# Ultimate Revision Sheet

Agar mujhe Amazon SDE-1 ke liye sirf **15 DP questions** choose karne ho toh:

1. Climbing Stairs
2. House Robber
3. Unique Paths
4. Minimum Path Sum
5. 0/1 Knapsack
6. Partition Equal Subset Sum
7. Coin Change
8. Coin Change II
9. Longest Increasing Subsequence
10. Longest Common Subsequence
11. Edit Distance
12. Decode Ways
13. Distinct Subsequences
14. Matrix Chain Multiplication
15. Burst Balloons

Ye 15 questions karne ke baad tu DP ke almost saare important patterns dekh chuka hoga:

✅ 1D DP
✅ Grid DP
✅ Knapsack DP
✅ Unbounded Knapsack
✅ LIS Pattern
✅ String DP
✅ Palindrome DP
✅ Partition DP
✅ State Machine DP
✅ Counting DP

Meri advice: **Striver DP Playlist ke first 35-40 problems** cover kar le. Amazon SDE-1 ke liye uske baad jo DP aayega, uska pattern pehchanne ke chances bahut high ho jaate hain.
