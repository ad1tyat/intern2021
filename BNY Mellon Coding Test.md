# BNY Mellon Coding Test

## Nearest point in space

We have an array of points(x[i],y[i]) . Find the closest point in array to the point(a,b). If there are more than one points , return the one which is near the origin. 
(Only python-numpy  allowed)

## Analogous arrays

An array is said to be analogous to the secret array if the following conditions are true:

- The length of the array is equal to the secret array
- Each integer in the array lies in the interval [lowerBound,upperBound].
- The difference between each pair of consecutive integers of the array must be equal to the difference between the respective pair of consecutive integers in the secret array. In other words, let the secret array be [s[0],s[1],s[2],....s[n-1]], and let the analogous array be [a[0],a[1],......a[n-1]], then a[i+1]-a[i] must be equal to s[i-1]-s[i] for each i from 1 to n-1.       

Given the value of lowerBound and upperBound and the array of difference between    each pair of consecutive integers of the secret array, find the number of arrays that are analogous to the secret array. If there are no array analogous to the secret array, return 0.

    Sample:
    consecutiveDifference = [-2, -1, -2, 5]                               Output: 3
    lowerBound = 3
    upperBound = 10
    [3, 5, 6, 8, 3],[4, 6, 7, 9, 4],[5, 7, 8, 10, 5] are the arrays. 
    Constraints:
    	-1e9<=lowerBound,upperBound<=1e9  
        1<=n<=1e5 

## Coin Change Problem 

https://www.hackerrank.com/challenges/coin-change/problem              

## Image matching 

We are given two maps filled with 0’s and 1’s . 1 denotes land and 0 denotes sea. 
Group of 1’s form an island. We have to count the number of islands which have an exact same image in the other map. Number of rows and column in each grid is n.
Constraint :
1<=n<=50
Sample:

```
n = 3
0 1 0           0 1 1
1 0 1           1 0 0
1 0 1           1 0 1
```

Output: 1

Only island [[2,1],[3,1]] matches in both maps. 



​         