# Java Variables Inside a Method

```java
//For example, `i` and `j` variables are available in the `main` method only:
 
public class Maths {
  public static void main(String [] args) {
    int i, j;
    System.out.println("These two variables are available in main method only");
  }
}
```

Java variables defined inside a method cannot be used outside the scope of that method.