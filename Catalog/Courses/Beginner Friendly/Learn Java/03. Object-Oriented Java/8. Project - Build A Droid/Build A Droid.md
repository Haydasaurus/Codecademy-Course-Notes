Learn Java
# Build A Droid

We’ve set up a robot workshop to build some droids. All that’s missing are the instructions on how to create the robots and what they’ll do.

Can we write a Java class to help?

We’ll need to define the state and behavior of the droids using instance fields and methods. Let’s get to work!

---

Exercise:

## Defining a Droid

1. The **Droid.java** file is empty.

Start by defining the class `Droid`.

Don’t forget to include a `main()` method! You can leave it empty for now.

We want a `Droid` object that has the following state:

-   name
-   battery level

and the following behavior:

-   performing a task
-   stating its battery level

Hint: Here’s an example of defining a `Person` class with a `main()` method:
```java
public class Person {  
  public static void main(String[] args) {   

  }
}
```

```java
public class Droid {

  public static void main(String[] args) {
 
  }
}
```

2. Declare an instance field called `batteryLevel`. We want to store whole number values in this field.

Hint: Here’s an example of defining an instance field in `Person`:
```java
public class Person {
 
  int age;
 
  public static void main(String[] args) {
 
  }
}
```

```java
public class Droid {

  int batteryLevel;

  public static void main(String[] args) {
 
  }
}
```

3. Declare another instance field called `name` which will store our droid’s name.

What type should this be?

Hint: Since `name` will store the text of what we call the `Droid`, `String` would be best.
```java
public class Droid {

  int batteryLevel;
  String name;

  public static void main(String[] args) {
 
  }
}
```

4. Create a constructor method for the `Droid` class.

The method should have one parameter of `String droidName`.

Hint: Constructor methods are named after the class. Here’s an example in `Person` that has one parameter:
```java
public class Person {
 
  int age;
  public Person(int yearsAlive) {
 
  }
 
  public static void main(String[] args) {
 
  }
}
```

```java
public class Droid {

  int batteryLevel;
  String name;

  public Droid(String droidName) {
    
  }

  public static void main(String[] args) {
 
  }
}
```

5. Inside the constructor, assign the parameter value of `droidName` to the appropriate instance field.

Set the value of `batteryLevel` to `100`. Every new instance of `Droid` will have a `batteryLevel` of `100`.

Hint: Here’s an example of assigning a value to an instance field in the `Person` constructor:
```java
public class Person {
 
  int age;
 
  public Person(int yearsAlive) {
    age = yearsAlive;
  }
 
  public static void main(String[] args) {
 
  }
}
```

```java
public class Droid {

  int batteryLevel;
  String name;

  public Droid(String droidName) {
    name = droidName;
    batteryLevel = 100;
  }

  public static void main(String[] args) {
 
  }
}
```

## Declaring Instances of Droid

6. Inside `main()`, create a `new` instance of `Droid` named `"Codey"`.

Hint: Here’s an example of creating an instance of `Person`:
```java
public class Person {
 
  int age;
 
  public Person(int yearsAlive) {
    age = yearsAlive;
  }
 
  public static void main(String[] args) {
    Person patrick = new Person(32);
  }
}
```

Don’t forget the `new` keyword!

```java
public class Droid {

  int batteryLevel;
  String name;

  public Droid(String droidName) {
    name = droidName;
    batteryLevel = 100;
  }

  public static void main(String[] args) {
 
    Droid codey = new Droid("Codey");
  }
}
```

7. Print out the variable using `System.out.println()`.

Hint: 
```java
public class Person {
 
  int age;
 
  public Person(int yearsAlive) {
    age = yearsAlive;
  }
 
  public static void main(String[] args) {
    Person patrick = new Person(32);
    // printing the variable:
    System.out.println(patrick);
    // access the age field:
    System.out.println(patrick.age);
  }
}
```

```java
public class Droid {

  int batteryLevel;
  String name;

  public Droid(String droidName) {
    name = droidName;
    batteryLevel = 100;
  }

  public static void main(String[] args) {
 
    Droid codey = new Droid("Codey");

    System.out.println(codey);
    System.out.println(codey.name);
  }
}
```

8. That output isn’t very informative!

Define a `toString()` method within `Droid`.

The return type is `String`.

Inside `toString()`, `return` a string that introduces the `Droid` using their name.

Something like “Hello, I’m the droid: droidNameHere”

Hint: Here’s an example of a `toString()` method for `Person`:
```java
public class Person {
 
  int age;
 
 
  public String toString() {
    return "Hey there, I am " + age + " years old!";
  }
 
  public Person(int yearsAlive) {
    age = yearsAlive;
  }
 
  public static void main(String[] args) {
    Person patrick = new Person(32);
 
    System.out.println(patrick);
  }
}
```

```java
public class Droid {

  int batteryLevel;
  String name;

  public Droid(String droidName) {
    name = droidName;
    batteryLevel = 100;
  }

  public String toString() {
    return "Hello, I'm the droid: " + name;
  }

  public static void main(String[] args) {
 
    Droid codey = new Droid("Codey");

    System.out.println(codey);
  }
}
```

## Doing Droid Things

9. Define a new method: `performTask()`. This method should have a single parameter: `String task`.

This method does not return any value.

Hint: Here’s an example of defining a new method on `Person`:
```java
public class Person {
 
  int age;
 
 
  public void greetAnother(String name) {
    System.out.println("Hey there, " + name);
  }
 
  public Person(int yearsAlive) {
    age = yearsAlive;
  }
 
  public static void main(String[] args) {
    Person patrick = new Person(32);
 
    patrick.greetAnother("Laura");
    // prints: hey there, Laura
  }
}
```

```java
public class Droid {

  int batteryLevel;
  String name;

  public Droid(String droidName) {
    name = droidName;
    batteryLevel = 100;
  }

  public void performTask(String task) {
    
  }

  public String toString() {
    return "Hello, I'm the droid: " + name;
  }

  public static void main(String[] args) {
 
    Droid codey = new Droid("Codey");

    System.out.println(codey);
  }
}
```

10. Inside `performTask()`, print a statement like “`name` is performing task: `task`“.

For example, `codey.performTask("dancing");` will print:

```
Codey is performing task: dancing
```

```java
public class Droid {

  int batteryLevel;
  String name;

  public Droid(String droidName) {
    name = droidName;
    batteryLevel = 100;
  }

  public void performTask(String task) {
    System.out.println(name + " is performing task: " + task);
  }

  public String toString() {
    return "Hello, I'm the droid: " + name;
  }

  public static void main(String[] args) {
 
    Droid codey = new Droid("Codey");

    System.out.println(codey);
    codey.performTask("dancing");
  }
}
```

11. Performing tasks is hard work. After the print statement, set `batteryLevel` to be `10` less than it was before.

We’ll need to reassign the instance field to be the current value minus 10.

Hint: Here’s an example of manipulating the `age` instance field:
```java
public class Person {
 
  int age;
 
 
  public void ageOneYear() {
    age = age + 1;
  }
 
  public Person(int yearsAlive) {
    age = yearsAlive;
  }
 
  public static void main(String[] args) {
    Person patrick = new Person(32);
    System.out.println(patrick.age);
    // 32
    patrick.ageOneYear();
    System.out.println(patrick.age);
    // 33
  }
}
```

```java
public class Droid {

  int batteryLevel;
  String name;

  public Droid(String droidName) {
    name = droidName;
    batteryLevel = 100;
  }

  public void performTask(String task) {
    System.out.println(name + " is performing task: " + task);
    batteryLevel = batteryLevel - 10;
  }

  public String toString() {
    return "Hello, I'm the droid: " + name;
  }

  public static void main(String[] args) {
 
    Droid codey = new Droid("Codey");

    System.out.println(codey);
    codey.performTask("dancing");
  }
}
```

12. Have your `Droid` instance perform some tasks inside of `main()`.

Hint: For example, we had our instances do activities like “dancing” and “levitating”.
```java
codey.performTask("dancing");
margot.performTask("levitating");
```

```java
public class Droid {

  int batteryLevel;
  String name;

  public Droid(String droidName) {
    name = droidName;
    batteryLevel = 100;
  }

  public void performTask(String task) {
    System.out.println(name + " is performing task: " + task);
    batteryLevel = batteryLevel - 10;
  }

  public String toString() {
    return "Hello, I'm the droid: " + name;
  }

  public static void main(String[] args) {
 
    Droid codey = new Droid("Codey");

    System.out.println(codey);
    codey.performTask("dancing");
    codey.performTask("levitating");
  }
}
```

## Next steps

13. Create new instances and play around with methods. Here are some ideas to get you started:

-   Create a `energyReport()` method that prints the instance’s `batteryLevel`.
-   Create another instance.
-   Create a method `energyTransfer()` that exchanges `batteryLevel` between instances.

```java
public class Droid {

  int batteryLevel;
  String name;

  public Droid(String droidName) {
    name = droidName;
    batteryLevel = 100;
  }

  public void performTask(String task) {
    System.out.println(name + " is performing task: " + task);
    batteryLevel = batteryLevel - 10;
  }

  public void energyReport() {
    System.out.println("My current battery level is: " + batteryLevel + "%");
  }

  public void energyTransfer(int amount, Droid transferTo) {  
    batteryLevel -= amount;
    transferTo.batteryLevel += amount;
    System.out.println(name + " has transfered " + amount + "% of their battery.");
  }

  public String toString() {
    return "Hello, I'm the droid: " + name;
  }

  public static void main(String[] args) {
 
    Droid codey = new Droid("Codey");
    Droid margot = new Droid("Margot");
    Droid kevin = new Droid("Kevin");
    Droid sloth = new Droid("Sloth");

    System.out.println(codey);
    codey.performTask("Dancing");
    codey.performTask("Levitating");
    codey.performTask("Coding");
    codey.performTask("Gaming");
    codey.energyReport();
    codey.energyTransfer(50, margot);
    codey.energyReport();
    System.out.println("--------------------------------------------");

    System.out.println(margot);
    margot.performTask("Fishing");
    margot.performTask("Cooking");
    margot.performTask("Writing");
    margot.energyReport();
    margot.energyTransfer(110, kevin);
    margot.energyReport();
    System.out.println("--------------------------------------------");

    System.out.println(kevin);
    kevin.performTask("Kniting");
    kevin.performTask("Baking");
    kevin.energyReport();
    kevin.energyTransfer(180, sloth);
    kevin.energyReport();
    System.out.println("--------------------------------------------");
    
    System.out.println(sloth);
    sloth.performTask("Sleeping...");
    sloth.energyReport();
    System.out.println("--------------------------------------------");
  }
}
```