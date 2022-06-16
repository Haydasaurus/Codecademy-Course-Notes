# The static Keyword

```java
public class ATM{
  // Static variables
  public static int totalMoney = 0;
  public static int numATMs = 0;
 
  // A static method
  public static void averageMoney(){
    System.out.println(totalMoney / numATMs);
  }
```

Static methods and variables are declared as static by using the `static` keyword upon declaration.