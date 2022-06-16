# Static Methods and Variables

```java
public class ATM{
  // Static variables
  public static int totalMoney = 0;
  public static int numATMs = 0;
 
  // A static method
  public static void averageMoney(){
    System.out.println(totalMoney / numATMs);
  }
 
  public static void main(String[] args){
 
    //Accessing a static variable
    System.out.println("Total number of ATMs: " + ATM.numATMs); 
 
    // Calling a static method
    ATM.averageMoney();
  }
 
}
```

Static methods and variables are associated with the class as a whole, not objects of the class. Both are used by using the name of the class followed by the `.` operator.