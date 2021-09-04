# Uber Coding Test
- Time: 1hr
- Questions: 3
- Point division: 100 / 300 / 300 roughly, 2nd or 3rd might've been worth more.
- Platform: Codesignal
- Shortlist for Interview: 16 students, mostly 3/3 solved.

## Question 1: 100 pts
Given a binary string, convert it into a base6 string.
#### Constraints
- `length of string <= 100`

## Question 2: 300 pts
You have to make a building of n floors. Each floor can be one of 3 types: an Office floor, a Cafeteria floor or a Residential floor. However, you have to follow two rules:
1. You **cannot** place **more than 2** Office floors consecutively.
2. There can be **atmost one** Cafeteria floor in the building.  

Find the number of ways to build the building, **mod 1e9+7**.
#### Constraints
- `1 <= n <= 1e5`

## Question 3: 300 pts
Given an array of size n, and two non-negative integers l and r, Find the number of ways to fill the array with numbers in range `[l, r]` such that the sum of the array divisible by 3.  
More formally, find the number of ways to fill the array `[a1, a2, .... an]` such that:
1. `l <= ai <= r` for all ai.
2. `a1 + a2 + ... an` is divisible by 3.  

Output the answer **mod 1e7+1**.  
**PS** You can use numbers multiple times. eg. for n = 4, `[1, 2, 2, 1]` is a valid way to fill the array.  
#### Constraints
- `1 <= n <= 1e6`
- `0 <= l <= r <= 1e6` might've been 1e9.
