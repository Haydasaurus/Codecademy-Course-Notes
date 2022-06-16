# Initializer Lists

```java
// Method one: declaring and intitializing at the same time
double[][] doubleValues = {{1.5, 2.6, 3.7}, {7.5, 6.4, 5.3}, {9.8,  8.7, 7.6}, {3.6, 5.7, 7.8}};
 
// Method two: declaring and initializing separately:
String[][] stringValues;
stringValues = new String[][] {{"working", "with"}, {"2D", "arrays"}, {"is", "fun"}};
```

In Java, initializer lists can be used to quickly give initial values to 2D arrays. This can be done in two different ways.

1.  If the array has not been declared yet, a new array can be declared and initialized in the same step using curly brackets.
    
2.  If the array has already been declared, the `new` keyword along with the data type must be used in order to use an initializer list