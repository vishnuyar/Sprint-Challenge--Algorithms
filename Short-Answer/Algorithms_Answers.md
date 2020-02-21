#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Run time complexity is O(n). Even though the while loop is for O(n^3), within the loop a is being added with (n^2) due to which the while loop exit will happen after O(n) time.


b) The for loop comlexity is O(n) and the while loop complexity is O(n/2), total run time complexity then is O(n^2/2)


c) As this is the recursive function , run time complexity is O(n)

## Exercise II

This is a binary search method which needs to be implemented such that the dropped eggs + broken eggs can be minimized

no_of_floors = n
previous_middle = 0
middle =  (no_of_floors/2)
while absolute difference(previous middle - middle)  <=1
drop egg from middle
previous_middle = middle
if egg breaks
   middle = middle/2
else
   middle = (no_of_floors - middle)/2

When the difference between the previous middle and new middle is less than or equal to one floor, we have identified f floor.

As this is binary search sort, the run time complextity is O(log n)
