# The this Keyword with Variables

```java
public class Dog{
  public String name;
 
  public void speak(String name){
    // Prints the instance variable named name
    System.out.println(this.name);
 
    // Prints the local variable named name
    System.out.println(name);
  }
}
```

In Java, the `this` keyword can be used to designate the difference between instance variables and local variables. Variables with `this.` reference an instance variable.