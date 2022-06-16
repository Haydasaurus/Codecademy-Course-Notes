# Polymorphism in Java

```java
// Parent class
class Animal {
  public void greeting() {
    System.out.println("The animal greets you.");
  }
}
 
// Child class
class Cat extends Animal {
  public void greeting() {
    System.out.println("The cat meows.");
  }
}
 
class MainClass {
  public static void main(String[] args) {
    Animal animal1 = new Animal();  // Animal object
    Animal cat1 = new Cat();  // Cat object
    animal1.greeting(); // prints "The animal greets you."
    cat1.greeting(); // prints "The cat meows."
  }
}
```

Java incorporates the object-oriented programming principle of _polymorphism_.

Polymorphism allows a child class to share the information and behavior of its parent class while also incorporating its own functionality. This allows for the benefits of simplified syntax and reduced cognitive overload for developers.