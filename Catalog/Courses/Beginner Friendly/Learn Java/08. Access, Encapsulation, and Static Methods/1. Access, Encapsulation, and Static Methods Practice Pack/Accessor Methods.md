# Accessor Methods

```java
public class CheckingAccount{
  private int balance;
  
  //An accessor method
  public int getBalance(){
    return this.balance;
  }
}
```

In Java, accessor methods return the value of a `private` variable. This gives other classes access to that value stored in that variable. without having direct access to the variable itself.

Accessor methods take no parameters and have a return type that matches the type of the variable they are accessing.