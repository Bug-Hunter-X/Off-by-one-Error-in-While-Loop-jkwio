# Off-by-one Error in Java While Loop

This repository demonstrates a common off-by-one error in Java that can be tricky to identify. The error occurs in a while loop where the loop counter is incremented within the loop's condition. This seemingly small detail can lead to unexpected behavior and incorrect results.

## Bug Description
The `bug.java` file contains a while loop that is intended to print numbers from 0 to 9. However, due to the post-increment operator (++), the loop actually prints numbers from 1 to 10. 

## Solution
The `bugSolution.java` file demonstrates the correct implementation of the while loop.  The solution employs a pre-increment operator or adjusts the loop's termination condition to fix the error.