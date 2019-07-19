Add your answers to the Algorithms exercises here.

### Exercise I

a) O(n)

The condition in while loop is n^3 but it is being cancelled by n * n in the body of while loop. Thus, it's time complexity is O(n) 

b) O(n^4)

This algorithm has four for loop nested inside of each other. If we ignore small constants in this algorithm, it's time complexity will be O(n^4)

c) O(n)

bunnyEars is a recursive function and it's calling itself once while reducing the n by one with each call. Thus, it's time complexity is O(n)