#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
-O(n)
-There is one while loop and the time complexity always relies on the size of n

b)
-O(n^2)
-There is a nested loop

c)
-O(n)
-It's calling a recursive function until it hits zero

## Exercise II

Using a binary search I would find the middle floor (middle_one) and drop an egg.  If the egg breaks, I would find the middle floor (middle_two) of the floors below middle_one and drop another egg.  If the egg does NOT break, I would find the middle floor of the floors above middle_two but still below middle_one.  I would repeat this process until I find the value of f which makes it a runtime complexity of O(logn)