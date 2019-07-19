Add your answers to the Algorithms exercises here.

### Exercise I

a) O(n)

The condition in while loop is n^3 but it is being cancelled by n * n in the body of while loop. Thus, it's time complexity is O(n) 

b) O(n^3)

This algorithm has four for loop nested inside of each other. If we ignore small constants in this algorithm, it's time complexity will be O(n^3)

c) O(n)

bunnyEars is a recursive function and it's calling itself once while reducing the n by one with each call. Thus, it's time complexity is O(n)

### Exercise II

As per the problem description, we need to find the solution in minimum number of drops, and not minimum number of broken eggs. So we can use binary search as the solution:

find middle floor of the building
drop the egg from that floor
if dropped egg breaks
    find the middle floor between the lowest floor and the floor from which egg was dropped
if dropped egg doesn't break
    find the middle floor between the highest floor and the floor from which egg was dropped
then repeat the above steps by dropping the egg from new middle floor
return the floor number from which egg doesn't break and upper floor minus lower floor is equal to one

Runtime complexity of this algorithm is O(log n). That means if we have a 100 story building, we will find the egg breaking floor by dropping 7 eggs.