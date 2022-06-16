# Static Methods and the this Keyword

```java
public class DemoClass{
 
  public int demoVariable = 5;
 
  public void demoNonStaticMethod(){
    
  }
  public static void demoStaticMethod(){
    // Can't use "this.demoVariable" or "this.demoNonStaticMethod()"
  }
}
```

Static methods do not have a `this` reference and are therefore unable to use the class’s instance variables or call non-static methods.