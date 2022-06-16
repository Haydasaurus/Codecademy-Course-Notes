# Java Program Structure
Java programs have a specific structure. Let’s take a closer look at the Hello World program — line by line!

Java programs have a specific structure in how the code is written. There are key elements that all Java programs share.

## The Program
We have the text of a program inside the file called **HelloWorld.java**.

```java
// This program outputs the message "Hello World!" to the monitor 

public class HelloWorld {  
	public static void main(String[] args) {    
		System.out.println("Hello World!");  
	}
}
```

This program writes `Hello World!` to your terminal when run.

### Case-Sensitivity
Java is a case-sensitive language. Case sensitivity means that _syntax_, the words our computer understands, must match the case. For example, the Java command for outputting text to the screen is `System.out.println()`. If you were to type `system.out.println()` or `System.Out.println()`, the compiler would not know that your intention was to use `System` or `out`.

Let’s go over this **HelloWorld.java** program line by line:

### Comments
```java
// This program outputs the message "Hello World!" to the monitor
```

This is a single-line comment that documents the code. The compiler will ignore everything after `//` to the end of the line. Comments provide information outside the syntax of the language.

### Classes
```java
public class HelloWorld {  
	// class code
}
```

This is the class of the file. All Java programs are made of at least one class. The class name must match the file: our file is **HelloWorld.java** and our class is `HelloWorld`. We capitalize every word, a style known as _pascal case_. Java variables and methods are named in a similar style called _camel case_ where every word **after the first** is capitalized.

The curly braces, `{` and `}`, mark the _scope_ of the class. Everything inside the curly braces is part of the class.

### Methods
```java
public static void main(String[] args) {   
	// Statements  
}
```

Every Java program must have a method called `main()`. A method is a sequence of tasks for the computer to execute. This `main()` method holds all of the instructions for our program.

### Statements
```java
System.out.println("Hello World!");
```

This code uses the method `println()` to send the text “Hello World!” to the terminal as output. `println()` comes from an _object_ called `out`, which is responsible for various types of output. Objects are packages of state and behavior, and they’re often modeled on real-world things.

`out` is located within `System`, which is another object responsible for representing our computer within the program! We can access parts of an object with a `.`, which is known as _dot notation_.

This line of code is a _statement_, because it performs a **single** task. Statements always conclude with a semicolon.

### Whitespace
Java programs allow judicious use of whitespace (tabs, spaces, newlines) to create code that is easier to read. The compiler ignores whitespace, but humans need it! Use whitespace to indent and separate lines of code. Whitespace increases the readability of your code.

### Practice
The structure of a Java program will feel familiar the more you work with this language. Continue learning at Codecademy and you’ll be a Java pro in no time!

---

#### For bookmarking:

-   [Twitter Java Style Guide](https://github.com/twitter/commons/blob/master/src/java/com/twitter/common/styleguide.md)
    
-   [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)