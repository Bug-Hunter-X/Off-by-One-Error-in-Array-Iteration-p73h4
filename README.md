This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error occurs because the loop condition `i <= arr.length` should be `i < arr.length`. The solution demonstrates the correct way to iterate to avoid the error.  The `Bug.java` file contains the erroneous code, and `BugSolution.java` contains the corrected version.