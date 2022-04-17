# Method parameters in Java

```java
public class Maths {
  public int sum(int a, int b) {
    int k = a + b;
    return k;
  }
  
  public static void main(String [] args) {
    Maths m = new Maths();
    int result = m.sum(10, 20);
    System.out.println("sum is " + result);
    // prints - sum is 30
  }
}
```

In java, parameters are declared in a method definition. The parameters act as variables inside the method and hold the value that was passed in. They can be used inside a method for printing or calculation purposes.

In the example, a and b are two parameters which, when the method is called, hold the value 10 and 20 respectively.