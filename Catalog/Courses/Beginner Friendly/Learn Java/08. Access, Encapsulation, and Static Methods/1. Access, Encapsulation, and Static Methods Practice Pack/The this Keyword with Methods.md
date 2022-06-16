# The this Keyword with Methods

```java
public class ExampleClass{
  public void exampleMethodOne(){
    System.out.println("Hello");
  }
 
  public void exampleMethodTwo(){
    //Calling a method using this.
    this.exampleMethodOne();
    System.out.println("There");
  }
}
```

In Java, the `this` keyword can be used to call methods when writing classes.
