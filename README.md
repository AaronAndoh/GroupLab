# GroupLab

The program contains a function called populateArray() that randomises the indicies of an array a certain number of time and SearchesValidEnteries() that creates a boundary to prints the indicies of the array in that boundary

1. create a function called populateArray that takes parameters an Array and integer N
2. Using randomiser in C++ ,create a for loop which randomises i and j N times and Prints the values of i and j.
3. if and else statment to assign 1 to the array A[i][j] when the value is 0 and add 1 if otherwise
4. create a function SearchesValidEnteries() that takes parameters Array and integer XL , integer YL, integer XH, integer YH which represents the boundary of the box
5. Using a for nested loop ,keep looping through the rows of the array to find the boundaries. where e represents the XL, XH and q represents the YL,YH respectively
6. if if the A[e][q] greater than 0 , print out the e and q with A[e][q]
7. in the main, create an array[101][101] and name it E and assign it to {0}.
8. call the populateArray(E,30)
9. call the SearchesValidEnteries(E,80,1,100,10)
