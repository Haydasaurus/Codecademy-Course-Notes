# The body of a Java method

```java
public class Maths {
  public static void sum(int a, int b) { // Start of sum
    int result = a + b;
    System.out.println("Sum is " + result);
  } // End of sum
  
  
  public static void main(String [] args) {
    // Here, we call the sum method
    sum(10, 20);
    // Output: Sum is 30
  }
}
```

In Java, we use curly brackets `{}` to enclose the body of a method.

The statements written inside the `{}` are executed when a method is called.