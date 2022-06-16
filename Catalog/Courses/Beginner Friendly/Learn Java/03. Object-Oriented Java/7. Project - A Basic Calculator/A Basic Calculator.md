Learn Java
# A Basic Calculator

In this project, you will use classes, methods, and objects to create a simple arithmetic calculator. The calculator will be able to:

-   Add two integers
-   Subtract two integers
-   Multiply two integers
-   Divide two integers
-   Apply the modulo operator on two integers

The instructions provided are general guidelines. Upon completion of the project, feel free to explore more in the learning environment.

**Important:** Moving forward, all projects will require that you define the `main` method manually. When you click the “Save” button below, an attempt to run your Java code is made. However, Java will return an error if you attempt to run a Java program without first defining a `main` method. If you encounter such an error, do not worry, you can define the `main` method ahead of time in order to avoid seeing the error.

---

Exercise:

1. Create a `public` class called `Calculator`.

Hint: To create a class called Abacus, for example, you could use syntax like:
```java
public class Abacus{ 

}
```

```java
public class Calculator { 

}
```

2. Inside of the class, create a `Calculator()` constructor. You can leave the contents of the constructor empty.

Hint: To create a constructor for an Abacus class, you could use syntax like:
```java
public class Abacus{
 
  public Abacus(){
 
  }
}
```

```java
public class Calculator{

  public Calculator(){
    
  }
}
```

3. Next, create a `public` method that returns an `int` and call it `add()`.

Hint: To make a method called `do_something()` that returns a `double`, for example, you would use syntax like:
```java
public double do_something(){ 

}
```

What syntax would you use for a method called `add()` that returns an `int`?

```java
public class Calculator{

  public Calculator() {
    
  }

  public int add(){
      
  }
}
```

4. The `add()` method should accept two `int` parameters. For example: `int a, int b`.

Hint: To add two `double` parameters to a method called `do_something()`, you would use syntax like:
```java
public double do_something(double first_param, double second_param){ 

}
```

How would you make them two `int` parameters instead?

```java
public class Calculator{

  public Calculator() {
    
  }

  public int add(int a, int b){
      
  }
}
```

5. The `add` method should add the two integer parameters that a user will specify. Inside of the `add` method, `return` the sum of `a` and `b`.

Hint: To return a variable called `result` from the function, you would use syntax like:
```java
return result;
```

How would you return `a` plus `b`?

```java
public class Calculator{

  public Calculator() {
    
  }

  public int add(int a, int b){
    return a + b;
  }
}
```

6. Next, create another similar method called `subtract()`. The `subtract()` method should accept two `int` parameters, just like the `add()` method does.

```java
public class Calculator{

  public Calculator() {
    
  }

  public int add(int a, int b){
    return a + b;
  }

  public int subtract(int a, int b){

  }
}
```

7. Inside of the `subtract()` method, `return` the difference of `a` and `b`.

```java
public class Calculator{

  public Calculator() {
    
  }

  public int add(int a, int b){
    return a + b;
  }

  public int subtract(int a, int b){
    return a - b;
  }
}
```

8. Create another method called `multiply()`. The `multiply()` method should accept two `int` parameters.

```java
public class Calculator {

  public Calculator() {
    
  }

  public int add(int a, int b) {
    return a + b;
  }

  public int subtract(int a, int b) {
    return a - b;
  }

  public int multiply(int a, int b) {

  }
}
```

9. Inside of the `multiply` method, `return` the product of `a` and `b`.

```java
public class Calculator {

  public Calculator() {
    
  }

  public int add(int a, int b) {
    return a + b;
  }

  public int subtract(int a, int b) {
    return a - b;
  }

  public int multiply(int a, int b) {
    return a * b;
  }
}
```

10. Create another method called `divide()`. It should accept two `int` parameters.

```java
public class Calculator {

  public Calculator() {
    
  }

  public int add(int a, int b) {
    return a + b;
  }

  public int subtract(int a, int b) {
    return a - b;
  }

  public int multiply(int a, int b) {
    return a * b;
  }

  public int divide(int a, int b) {

  }
}
```

11. Inside of the `divide()` function, return `a` divided by `b`.

```java
public class Calculator {

  public Calculator() {
    
  }

  public int add(int a, int b) {
    return a + b;
  }

  public int subtract(int a, int b) {
    return a - b;
  }

  public int multiply(int a, int b) {
    return a * b;
  }

  public int divide(int a, int b) {
    return a / b;
  }
}
```

12. Create another method called `modulo`. It should accept two `int` parameters.

```java
public class Calculator {

  public Calculator() {
    
  }

  public int add(int a, int b) {
    return a + b;
  }

  public int subtract(int a, int b) {
    return a - b;
  }

  public int multiply(int a, int b) {
    return a * b;
  }

  public int divide(int a, int b) {
    return a / b;
  }

  public int modulo(int a, int b) {

  }
}
```

13. Inside of the `modulo()` function, return `a` modulo `b`.

```java
public class Calculator {

  public Calculator() {
    
  }

  public int add(int a, int b) {
    return a + b;
  }

  public int subtract(int a, int b) {
    return a - b;
  }

  public int multiply(int a, int b) {
    return a * b;
  }

  public int divide(int a, int b) {
    return a / b;
  }

  public int modulo(int a, int b) {
    return a % b;
  }
}
```

14. Next, create a `main()` method. Can you remember all the keywords necessary for a `main()` method?

Hint: The `main()` method is defined exactly the same way for every class:
```java
public static void main(String[] args){ 

}
```

```java
public class Calculator {

  public Calculator() {
    
  }
  
  public int add(int a, int b) {
    return a + b;
  }

  public int subtract(int a, int b) {
    return a - b;
  }

  public int multiply(int a, int b) {
    return a * b;
  }

  public int divide(int a, int b) {
    return a / b;
  }

  public int modulo(int a, int b) {
    return a % b;
  }

  public static void main(String[] args) {
 
  }
}
```

15. Inside of `main()`, create a `Calculator` object called `myCalculator`.

Hint: To create a new `Dog` Object, we would use syntax like:
```java
Dog myDog = new Dog();
```

How would you do this for the Calculator class?

```java
public class Calculator {

  public Calculator() {
    
  }

  public int add(int a, int b) {
    return a + b;
  }

  public int subtract(int a, int b) {
    return a - b;
  }

  public int multiply(int a, int b) {
    return a * b;
  }

  public int divide(int a, int b) {
    return a / b;
  }

  public int modulo(int a, int b) {
    return a % b;
  }

  public static void main(String[] args) {
    Calculator myCalculator = new Calculator();
  }
}
```

16. Print out the value of calling the `add()` method on `myCalculator`. Pass in `5` and `7` as parameters.

Hint: You can either print the result directly:
```java
System.out.println(myCalculator.add(5, 7));
```

Or save the result to a variable, and then print the variable:
```java
int addition = myCalculator.add(5, 7);
System.out.println(addition);
```

```java
public class Calculator {

  public Calculator() {
    
  }

  public int add(int a, int b) {
    return a + b;
  }

  public int subtract(int a, int b) {
    return a - b;
  }

  public int multiply(int a, int b) {
    return a * b;
  }

  public int divide(int a, int b) {
    return a / b;
  }

  public int modulo(int a, int b) {
    return a % b;
  }

  public static void main(String[] args) {
    Calculator myCalculator = new Calculator();
    
    System.out.println(myCalculator.add(5, 7));
  }
}
```

17. On the next line, print out the value of calling the `subtract()` method on `myCalculator`. Pass in `45` and `11` as parameters.

Hint: You can either print the result directly:
```java
System.out.println(myCalculator.subtract(45, 11));
```

Or save the result to a variable, and then print the variable:
```java
int subtraction = myCalculator.subtract(45, 11);
System.out.println(subtraction);
```

```java
public class Calculator {

  public Calculator() {
    
  }

  public int add(int a, int b) {
    return a + b;
  }

  public int subtract(int a, int b) {
    return a - b;
  }

  public int multiply(int a, int b) {
    return a * b;
  }

  public int divide(int a, int b) {
    return a / b;
  }

  public int modulo(int a, int b) {
    return a % b;
  }

  public static void main(String[] args) {
    Calculator myCalculator = new Calculator();

    System.out.println(myCalculator.add(5, 7));
    System.out.println(myCalculator.subtract(45, 11));
  }
}
```

18. If you completed this project correctly, the output should be `12` and `34`. Feel free to explore more with the program. What are some ways in which the program could be improved?

Hint: You could add methods that work with `double`s, for example!

19. Add comments near the top of the program that describe what the program does.

Hint: For example, you could add a comment like:
```java
/*
This is an Abacus that is used to slide beads around and do math.
It was created by Laura in 2019.
*/
```

```java
/*
This is a basic calculator for integers
Created by Hayden - 2022
*/

public class Calculator {

  // Initial instance of a Calculator to call in the main method
  public Calculator() {
    
  }

  // Allows for the addition of integers
  public int add(int a, int b) {
    return a + b;
  }

  // Allows for the subtraction of integers
  public int subtract(int a, int b) {
    return a - b;
  }

  // Allows for the multiplication of integers
  public int multiply(int a, int b) {
    return a * b;
  }

  // Allows for the division of integers
  public int divide(int a, int b) {
    return a / b;
  }

  // Shows the remainder after the division of integers
  public int modulo(int a, int b) {
    return a % b;
  }

  // The main method where the integers and their expressions are ran
  public static void main(String[] args) {
    Calculator myCalculator = new Calculator();

    System.out.println(myCalculator.add(5, 7));
    System.out.println(myCalculator.subtract(45, 11));
  }
}
```