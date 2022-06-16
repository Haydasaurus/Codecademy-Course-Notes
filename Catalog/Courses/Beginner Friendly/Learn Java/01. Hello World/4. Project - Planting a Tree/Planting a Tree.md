Learn Java
# Planting a Tree

Introduce yourself to users and plant a tree for them!

```java
// Define your tree class in this file!
```

### Creating the Class
1. We’re starting with a blank Java file named **Tree.java**.

Define a class that follows the Java naming conventions.

Hint: Java naming conventions have class names matching file names.
For example, here is how to define a class in the file **MyExample.java**.
```java
public class MyExample {  
	// class code goes here
}
```

```java
public class Tree {
}
```

2. This code produces an error because our program needs a `main()` method.

Define this method inside the curly braces of the `Tree` class.

Hint: We use the same main method declaration for every class:
```java
public class Dog {
  public static void main(String[] args) {
    // code for main method goes here
  }
}
```

```java
public class Tree {
  public static void main(String[] args) {
  }
}
```

3. Write a comment in `main()` that describes the task it will perform.

We’re going to introduce ourselves and print a tree to the screen.

You can use the single-line or multi-line syntax for your comment.

Hint: 
```java
public class Dog {
  public static void main(String[] args) {
    // I am a single line comment
 
 
    /* It would appear that I, humble though
       I may be, have been chosen as the 
       multi-line comment for this example */
  }
}
```

```java
public class Tree {
  public static void main(String[] args) {
    //We’re going to introduce ourselves and print a tree to the screen. 
  }
}
```

4. Below your comment, print a message introducing yourself to the user.

Try something like “Hey there, I’m Ariel and I’m learning to code in Java!”

When you run the code, you should see this message printed to the screen.

Hint: We can print to the screen like so:
```java
System.out.println("I will be printed to the screen");
```
Note that we use double quotes and end the statement with a semicolon!

```java
public class Tree {
  public static void main(String[] args) {
    //We’re going to introduce ourselves and print a tree to the screen. 
    System.out.println("Hey there, I’m Hayden and I’m learning to code in Java!");
  }
}
```

### Planting Trees
5. After introducing yourself, use another print statement to output the project goal!

Something like “I’m going to plant a tree today!” or “Ready to get my hands dirty!”

```java
public class Tree {
  public static void main(String[] args) {
    //We’re going to introduce ourselves and print a tree to the screen. 
    System.out.println("Hey there, I’m Hayden and I’m learning to code in Java!");
    System.out.println("I’m going to plant a tree today!");
  }
}
```

6. See how the second statement begins on a new line? We’ll use multiple print statements to plant our tree.

For example:
```java
	System.out.println("  *  ");
    System.out.println(" *** ");
    System.out.println(" *** ");
    System.out.println("  *  ");
    System.out.println("  *  ");   
```

will print a tree like this:
```bash
  *  
 *** 
 *** 
  *  
  *  
```

Try it out!

```java
public class Tree {
  public static void main(String[] args) {
    // This code will introduce myself and print a tree onto the screen
    System.out.println("Hello, my name is Hayden Gilbert, this is my first Java Program.");
    System.out.println("I will now print a tree.");
      System.out.println("   *   ");
      System.out.println("  ***  ");
      System.out.println(" ***** ");
      System.out.println("   *   ");
  }
}
```

7. Have fun and experiment with different trees.

Here are a couple we made:
```bash
 * ** * 
 ****** 
  ****  
   **   
   **   
~~~~~~~~~~
```

```bash
 ***** 
 ***** 
 ***** 
   *   
   *   
#######
```

You can explore other printing methods in the [Java documentation](https://docs.oracle.com/javase/8/docs/api/java/lang/System.html#out).