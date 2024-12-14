# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common programming error in Java: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that produces this exception. The `bugSolution.java` file provides the corrected code.

## Bug Description

The bug occurs because the loop iterates one time too many, trying to access an element that does not exist in the array.  This results in an `ArrayIndexOutOfBoundsException` at runtime.

## Solution

The solution involves correcting the loop condition to ensure it only iterates within the valid bounds of the array. The corrected loop condition should be `i < arr.length` instead of `i <= arr.length`.