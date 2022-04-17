The `main()` method is automatically run when the **.class** file is executed.
True

(We never need to call `main()` ourselves)

---

Instances of a Java class represent the real world with what two qualities?
State and Behavior

(State is represented with instance fields and behavior is represented with methods)

---

The `Bank` class has one instance field: `branchLocationCount`.

Complete the constructor method for this class.

```java
public class Bank {
  int branchLocationCount;
  
  public Bank(  ?  ) {
    branchLocationCount = numLocations;
  }
  public static void main(String[] args) {
    // program tasks
  }
}
```

int numLocations

---

What is the signature of the following constructor?

```java
public class Bug {
  String name;
  boolean ableToFly;
  int numberOfLegs;
 
  public Bug(String bugName, boolean canFly, int numLegs) {
    name = bugName;
    ableToFly = canFly;
    numberOfLegs = numLegs;
  }
  public static void main(String[] args) {
    Bug ladybug = new Bug("Lady Bug", true, 6);
  }
}
```

Bug(String bugName, boolean canFly, int numLegs)

(A signature consists of the constructor’s name and then the data type and name of each of its parameters)

---

Every Java program contains at least one class.
True

(Java programs always require one class, and real-world programs can contain hundreds)

---

Complete the following class definition for a `Bank` class.

```java
public ? Bank {
  public static void main(String[] args) {
    // program tasks
  }
}
```

class

---

An instance is declared in the `main()` function. Complete the method call.

```java
public class Window {
  boolean isOpen;
  int height;
  int width;
  
  public Window(boolean open, int windowHeight, int windowWidth) {
    isOpen = open;
    height = windowHeight;
    width = windowWidth;
  }
  
  public static void main(String[] args) {
    Window bedroomWindow = ?
  }
}
```

new Window(true, 72, 34);

---

What is the data type of the variable `hedwig`?

```java
public class Owl {
  String speak;
  boolean nocturnal;
  public Owl() {
    speak = "Hoot";
    nocturnal = true;
  }  
 
  public static void main(String[] args) {
    Owl hedwig = new Owl();
  }
}
```

Owl

(The `hedwig` variable has a reference data type. When declaring a variable with a reference data type, the variable’s type is the name of a class)

---

Why will the following program produce an error?

```java
public class Shelf {
 
  String material;
  
  public Shelf() {
  
  }
  
  public static void main(String[] args) {
    Shelf bureau = new Shelf("pine");
  }
}
```

The constructor does not have a parameter listed.

(We cannot invoke the constructor with a parameter unless it has been listed in the method)

---

The following class definition requires a parameter to be passed in to the constructor in order to make an instance.

```java
public class Dinosaur {
  boolean isExtinct;
  
  public Dinosaur(boolean extinct) {
    isExtinct = extinct;
  }
  
  public static void main(String[] args) {
    // program tasks
  }
}
```

True

(To make an instance of `Dinosaur` we need to pass a `boolean` into the constructor invocation)