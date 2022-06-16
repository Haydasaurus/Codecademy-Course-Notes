# Static Methods with Instance Variables

```java
class ATM{
// Static variables
  public static int totalMoney = 0;
  public static int numATMs = 0; 
 
  public int money = 1;
 
  // A static method
  public static void averageMoney(){
    // Can not use this.money here because a static method can't access instance variables
  }
 
}
```

Static methods cannot access or change the values of instance variables.