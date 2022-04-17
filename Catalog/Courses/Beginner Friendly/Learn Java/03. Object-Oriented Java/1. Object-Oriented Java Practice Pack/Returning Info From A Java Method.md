# Returning info from a Java method

```java
public class Maths { 
  
  // return type is int
  public int sum(int a, int b) {
    int k;
    k = a + b;
    
    // sum is returned using the return keyword
    return k;
  }
  
  public static void main(String [] args) {
    Maths m = new Maths();
    int result;
    result = m.sum(10, 20);
    System.out.println("Sum is " + result);
    // Output: Sum is 30
  }
}
```

A Java method can return any value that can be saved in a variable. The value returned must match with the return type specified in the method signature.

The value is returned using the `return` keyword.