# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common error in Java: the `ArrayIndexOutOfBoundsException`. The error occurs when accessing an array element using an index that is out of bounds (either negative or greater than or equal to the array's length).  The provided code snippet shows a simple example and the solution to avoid this error.

**Bug:** The for loop iterates one extra time resulting in an index out of bound exception.

**Solution:** The loop condition is corrected so that it only iterates up to the last valid index.