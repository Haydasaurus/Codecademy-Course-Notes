# super() in Java

```java
// Parent class
class Animal {
  String sound;
  Animal(String snd) {
    this.sound = snd;
  }
}
 
// Child class
class Dog extends Animal { 
  // super() method can act like the parent constructor inside the child class constructor.
  Dog() {
    super("woof");
  } 
  // alternatively, we can override the constructor completely by defining a new constructor.
  Dog() {
    this.sound = "woof";
  }
}
```

In Java, a child class inherits its parent’s fields and methods, meaning it also inherits the parent’s constructor. Sometimes we may want to modify the constructor, in which case we can use the `super()` method, which acts like the parent constructor inside the child class constructor.

Alternatively, we can also completely override a parent class constructor by writing a new constructor for the child class.