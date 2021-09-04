# Tower Research Coding Test

There were 9 MCQs on Networking, OS, DBMS and OOPS. They were medium-hard in difficulty

There were 2 coding questions and 2 debugging questions in which snippets were provided which had to be edited to pass testcases.

## Coding 1

https://www.interviewbit.com/problems/gas-station/ 

## Coding 2

Thor starts at coordinate (a, b), he wants to reach Loki at (c, d)

However he can only travel 

from (x, y) to (x +y ,y)

from (x, y) to (x, x + y)

determine if Thor can reach Loki

Example,

```
a = 1
b = 1
c = 5
d = 2
Ans = Yes
One possible path = (1,1) -> (1,2) -> (3,2) => (5,2)
```

## Debugging 1

An array is given. find the minimum value in for each subarray (contiguous) of length k> Among all these values, return the maximum

Example, 

```
n = 4
arr = [8, 2, 4, 6]
k = 2

Minimas = 2, 2, 4 of subarrays (8, 2), (2, 4), (4, 6)
Hence ans = Maximum = 4
```

## Debugging 2

There are n horizontal bars, m vertical bars. 

an array h is given, these horizontal bars are removed.

an array v is given, these vertical bars are removed.

Find out size of biggest square hole

Eg : n = 6, m = 6, h = [4], v = [2], ans = 4. Refer to figure
![image](https://user-images.githubusercontent.com/30773534/132053369-4fff80c8-ec77-4052-9273-b2089e852394.png)
