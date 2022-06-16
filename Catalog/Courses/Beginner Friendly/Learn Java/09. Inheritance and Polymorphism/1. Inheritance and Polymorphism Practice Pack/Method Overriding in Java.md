# Method Overriding in Java

```java
// Parent class 
class Animal {
  public void eating() {
    System.out.println("The animal is eating.");
  }
}
 
// Child class 
class Dog extends Animal {
  // Dog's eating method overrides Animal's eating method
    @Override
  public void eating() {
    System.out.println("The dog is eating.");
  }
}
```

In Java, we can easily _override_ parent class methods in a child class. Overriding a method is useful when we want our child class method to have the same name as a parent class method but behave a bit differently.

In order to override a parent class method in a child class, we need to make sure that the child class method has the following in common with its parent class method:

-   Method name
-   Return type
-   Number and type of parameters

Additionally, we should include the `@Override` keyword above our child class method to indicate to the compiler that we want to override a method in the parent class.