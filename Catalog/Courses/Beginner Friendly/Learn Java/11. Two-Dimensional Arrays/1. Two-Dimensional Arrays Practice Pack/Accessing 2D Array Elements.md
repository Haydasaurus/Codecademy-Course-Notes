# Accessing 2D Array Elements

```java
//Given a 2d array called `arr` which stores `int` values
int[][] arr = {{1,2,3},
               {4,5,6}};
 
//We can get the value `4` by using
int retrieved = arr[1][0];
```

In Java, when accessing the element from a 2D array using `arr[first][second]`, the `first` index can be thought of as the desired row, and the `second` index is used for the desired column. Just like 1D arrays, 2D arrays are indexed starting at `0`.