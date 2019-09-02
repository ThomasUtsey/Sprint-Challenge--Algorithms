#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)
O(n^3) n is multiplied by itself 3 times and requires a condition to be met as loop

b)
O( n log n) n runs until condition is met one time

c)
O(n) recursively nth times

## Exercise II

This can be solved via a binary search while splitting the total floors by n

mid = floors // 2 # this will split our array down the middle
we now define an upper and a lower
lower = floors[:mid +1]
upper = floors[mid + 1]
if egg breaks at mid floor
call function with lower and repeat
else
call function with upper and repeat

return
