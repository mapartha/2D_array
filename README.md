# 2D_array
Example of 2D Array in C
This example shows how to set a pointer to a one-dimensional array and
a two-dimensional array in C.
array1 is a 100-element 1D array (numbaers 1 to 100) which is accessed by pointer p1 and the output is displayed using a nested 'for' loop
array2 is a 10x10 2D array (numbaers 1 to 100)
array2 is accessed using an array of pointers p2, since a 2D array in C is an array of pointers to 1D arrays
pointer p3 is used to access 2D array2 uses malloc() but generates compiler warning and hence should not be used
pointer p4 is used to directly access 2D array2 without copying its contents
p4 also generates compiler warning and should not be used
