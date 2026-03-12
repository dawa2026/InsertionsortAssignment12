# InsertionsortAssignment12
Insertion Sort Program in C (Descending Order)
Overview

This program implements the Insertion Sort algorithm in the C programming language to sort numbers in descending order.
It allows the user to enter the number of elements and dynamically allocates memory to store the array.

     #How it Works#

1.Start from the second element of the array.

2.Store the current element as key.

3.Compare it with previous elements.

4.Shift smaller elements one position forward.

5.Insert the key in the correct position.
    #SUMMARY#
This program demonstrates how the Insertion Sort algorithm works in C.
It also shows the use of functions, loops, arrays, and dynamic memory allocation to build a flexible sorting program.

                         #Time Complexity Analysis#

The time complexity of the insertion sort algorithm depends on how the input data is arranged.

1.Best Case

-The best case occurs when the array is already sorted in descending order.

Example:

9 7 5 3 1

In this situation:

The while condition fails immediately.

Only one comparison is done for each element.

Therefore the time complexity is:
O(n)

2.Worst Case

The worst case occurs when the array is sorted in the opposite order (ascending).

Example:

1 3 5 7 9

For each element:

The algorithm compares it with all previous elements.

Many shifts occur inside the while loop.

Number of comparisons roughly becomes:

1 + 2 + 3 + ... + (n-1)

Which results in:
O(n²)

3.Average Case

In an average scenario where elements are randomly arranged:

Some comparisons occur

Some shifts occur

The average time complexity is also:

O(n²)

@Space Complexity

Insertion sort uses only a few additional variables (i, j, key).

Therefore the space complexity is:

O(1)

This means it is an in-place sorting algorithm.
