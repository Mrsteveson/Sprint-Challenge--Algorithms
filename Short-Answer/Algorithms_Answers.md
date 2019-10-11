#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Runtime = O(n).
Exercise 1.a looks to be a linear as the function scales with the size of the given input.


b) Runtime = O(n^2).
Exercise 1.b has a nested loop so I believe that would result in a n squared run time. 


c) Runtime = O(n).
Exercise 1.c also looks to be linear as we have no nested loops and our function is triggering a recursive call for every bunny input into this function.

## Exercise II

1) In this situation I believe a binary search would result in the fewest total amount of steps required to find our answer, with a runtime of O(log(n)).

First determine the total number of floors in the building, and calculate the midpoint. Once the midpoint is established, drop an egg from that floor to see if it breaks or not. If it does not break move to the midpoint of the top half of the building and try again. If it does break move to the midpoint of the bottom half of the building and try again. Repeat until we find the correct floor.

