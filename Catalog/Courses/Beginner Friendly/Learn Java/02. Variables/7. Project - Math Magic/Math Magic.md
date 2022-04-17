Learn Java
# Math Magic

In this project, you will become a mathemagician and write a small program that performs a mathematical magic trick! It will involve performing arithmetic operations on an integer that you choose.

The instructions provided are general guidelines. Upon completion of the project, feel free to explore the code on your own.

If you get stuck during this project or would like to see an experienced developer work through it, click “**Get Unstuck**“ to see a **project walkthrough video**.

---

Exercise: 

```java
public class Magic {
	public static void main(String[] args) {

		

	}
}
```

1. Create an `int` variable called `myNumber`.

Set it equal to any integer other than 0.

Hint: To declare and initialize:
```java
int myNumber = 2;
```

Remember that the semicolon `;` is used to end Java statements.

For this code to work properly, `myNumber` must be between -46341 and 46340.

```java
public class Magic {
	public static void main(String[] args) {
		int myNumber = 2;


	}
}
```

2. We will refer to `myNumber` as the original number from now on - it might be helpful to document this.

Write a comment in the program that documents this.

Hint: Single line comments are one line comments that begin with two forward slashes:
```java
// I'm a single line comment!
```

It would be helpful to let other programmers know that `myNumber` is the original number:
```java
// myNumber is the original number
```

```java
public class Magic {
	public static void main(String[] args) {
		int myNumber = 2; // Original number


	}
}
```

3. Create an `int` variable called `stepOne`.

Set it equal to the original number (`myNumber`) multiplied by itself.

Hint: Suppose you want to create an `int` variable called `tons` and set it equal to 4 × 4, you would write:
```java
int tons = 4 * 4;
```

```java
public class Magic {
	public static void main(String[] args) {
	    int myNumber = 2; // Original number
	    int stepOne = myNumber * myNumber;

	}
}
```

4. Create an `int` variable called `stepTwo`.

Set it equal to the previous result (`stepOne`) plus the original number (`myNumber`).

Hint: Suppose you want to create an `int` variable called `two` and set it equal to 1 + 1, you would write:
```java
int two = 1 + 1;
```

```java
public class Magic {
	public static void main(String[] args) {
	    int myNumber = 2; // Original number
	    int stepOne = myNumber * myNumber;
	    int stepTwo = stepOne + myNumber;
	}
}
```

5. Create an `int` variable called `stepThree`.

Set it equal to the previous result (`stepTwo`) divided by the original number.

Hint: To perform a division, use the forward slash `/`:
```java
int quotient = 45 / 3;
```

```java
public class Magic {
	public static void main(String[] args) {
	    int myNumber = 2; // Original number
	    int stepOne = myNumber * myNumber;
	    int stepTwo = stepOne + myNumber;
	    int stepThree = stepTwo / myNumber;
	}
}
```

6. Create an `int` variable called `stepFour`.

Set it equal to the previous result (`stepThree`) plus `17`.

```java
public class Magic {
	public static void main(String[] args) {
	    int myNumber = 2; // Original number
	    int stepOne = myNumber * myNumber;
	    int stepTwo = stepOne + myNumber;
	    int stepThree = stepTwo / myNumber;
	    int stepFour = stepThree + 17;
	}
}
```

7. Create an `int` variable called `stepFive`.

Set it equal to the previous result (`stepFour`) minus the original number.

Hint: To perform a subtraction, use the `-`:
```java
int subtraction = 20 - 15;
```

```java
public class Magic {
	public static void main(String[] args) {
	    int myNumber = 2; // Original number
	    int stepOne = myNumber * myNumber;
	    int stepTwo = stepOne + myNumber;
	    int stepThree = stepTwo / myNumber;
	    int stepFour = stepThree + 17;
	    int stepFive = stepFour - myNumber;
	}
}
```

8. Create an `int` variable called `stepSix`.

Set it equal to the previous result (`stepFive`) divided by `6`.

```java
public class Magic {
	public static void main(String[] args) {
	    int myNumber = 2; // Original number
	    int stepOne = myNumber * myNumber;
	    int stepTwo = stepOne + myNumber;
	    int stepThree = stepTwo / myNumber;
	    int stepFour = stepThree + 17;
	    int stepFive = stepFour - myNumber;
	    int stepSix = stepFive / 6;
	}
}
```

9. Print out the value of the last step.

Then, save and run your code!

What number is printed to the console?

Hint: 
```java
System.out.println(stepSix);
```

```java
public class Magic {
	public static void main(String[] args) {
	    int myNumber = 2; // Original number
	    int stepOne = myNumber * myNumber;
	    int stepTwo = stepOne + myNumber;
	    int stepThree = stepTwo / myNumber;
	    int stepFour = stepThree + 17;
	    int stepFive = stepFour - myNumber;
	    int stepSix = stepFive / 6;
	    System.out.println(stepSix);
	}
}
```

10. Now, go back to your code and change `myNumber` to any other integer. Run your program again.

Is the output the same?

It’s math magic!

Hint: `3` will be printed to the console no matter what integer you choose as the original number!
Want to know why?
[![](https://i.imgur.com/Qh9Lafa.gif)](https://imgur.com/Qh9Lafa)
Suppose `myNumber` is x:
**( ( ( x² + x ) / x ) + 17 - x ) / 6**
**= ( ( x + 1 ) + 17 - x ) / 6**
**= ( x + 18 - x ) / 6**
**= 18 / 6**
**= 3**

11. Great job completing this project! Want to keep challenging yourself?

Recreate this project using only two variables: `myNumber` and `magicNumber`. Use your understanding of compound assignment operators to recreate the above program by only manipulating `magicNumber`.

See the **Hint** for more help.

Hint: Here are the steps for accomplishing this task:

-   First, create the `myNumber` variable and set it equal to any number that is not `0`.    
```java
int myNumber = 15; // Can be any number
```

-   Then, declare a variable called `magicNumber` and initialize it to have the value `myNumber * myNumber`:    
```java
int magicNumber = myNumber * myNumber;
```
    
-   Next, use the `+=` compound assignment operator to increase the value of `magicNumber` by `myNumber`:
```java
magicNumber += myNumber;
```
    
-   Use `/=` to divide `magicNumber` by `myNumber`:
```java
magicNumber /= myNumber;
```
    
-   Use `+=` in increase `magicNumber` by `17`:
```java
magicNumber += 17;
```
    
-   Decrease `magicNumber` by `myNumber` using `-=`:
```java
magicNumber -= myNumber
```
    
-   Then, use `/=` to divide `magicNumber` by `6`:
```java
magicNumber /= 6;
```
    
-   Finally, print the value of `magicNumber` to check that your program works correctly!