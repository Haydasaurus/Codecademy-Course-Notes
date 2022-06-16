# Methods with Static Variables

```java
class ATM{
// Static variables 
  public static int totalMoney = 0; 
  public static int numATMs = 0; 
  public int money = 1;
 
 // A static method interacting with a static variable 
  public static void staticMethod(){ 
    totalMoney += 1;
   } 
 
  // A non-static method interactingwith a static variable 
  public void nonStaticMethod(){
    totalMoney += 1; 
  } 
}
```

Both non-static and static methods can access or change the values of static variables.