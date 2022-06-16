Learn Java
# Continents and Cities

Planet Earth is a magical place. Let’s practice the Java switch statement that you learned about.

Write a **Continents.java** program that will print out a continent and the largest city in that continent, based on the value of an integer.

The instructions provided are general guidelines. Upon completion of the project, feel free to add functionality of your own.

---

Exercise:

## Setting up:

1. Let’s create a skeleton for the program. Add:

```java
public class Continents {
 
  public static void main(String[] args) {
 
 
 
  }
 
}
```

Hint: The `main()` is the main function that houses your program.

```java
public class Continents {
	public static void main(String[] args) {
      
		

	}
}
```

2. Write a comment near the top of the program that describe what the program does.

Hint:
```java
// Continents and their largest cities.
```

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
		

	}
}
```

3. Create an `int` variable called `continent` and set it equal to `4`.

Hint:
```java
int continent = 4;
```

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;
		

	}
}
```

## Write a switch statement:

4. Create a `switch` statement that will switch based on the value of `continent`.

Hint:
```java
switch (continent) {
 
 
 
}
```

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        
      }		

	}
}
```

5. Inside of the switch statement, add a `case` that will run when the value of `continent` is `1`.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
        
      }		

	}
}
```

6. When the value of `continent` is `1`, print out `North America: Mexico City, Mexico`.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
	        System.out.println("North America: Mexico City, Mexico");
      }		

	}
}
```

7. Make sure the next line exits out of the case.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
          System.out.println("North America: Mexico City, Mexico");
          break;
      }		

	}
}
```

8. Add another `case` that will run when the value of `continent` is `2`. When this value is met, print out `South America: Sao Paulo, Brazil`.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
          System.out.println("North America: Mexico City, Mexico");
          break;
        case 2:
          System.out.println("South America: Sao Paulo, Brazil");
      }		

	}
}
```

9. Make sure the next line exits out of the case.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
          System.out.println("North America: Mexico City, Mexico");
          break;
        case 2:
          System.out.println("South America: Sao Paulo, Brazil");
          break;
      }		

	}
}
```

10. Add another `case` that will run when the value of `continent` is `3`. When this value is met, print out `Europe: Moscow, Russia`. Make sure the next line exits out of the case.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
          System.out.println("North America: Mexico City, Mexico");
          break;
        case 2:
          System.out.println("South America: Sao Paulo, Brazil");
          break;
        case 3:
          System.out.println("Europe: Moscow, Russia");
          break;
      }

	}
}
```

11. Add another `case` that will run when the value of `continent` is `4`. When this value is met, print out `Africa: Lagos, Nigeria`. Make sure the next line exits out of the case.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
          System.out.println("North America: Mexico City, Mexico");
          break;
        case 2:
          System.out.println("South America: Sao Paulo, Brazil");
          break;
        case 3:
          System.out.println("Europe: Moscow, Russia");
          break;
        case 4:
          System.out.println("Africa: Lagos, Nigeria");
          break;
      }

	}
}
```

12. Add another `case` that will run when the value of `continent` is `5`. When this value is met, print out `Asia: Shanghai, China`. Make sure the next line exits out of the case.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
          System.out.println("North America: Mexico City, Mexico");
          break;
        case 2:
          System.out.println("South America: Sao Paulo, Brazil");
          break;
        case 3:
          System.out.println("Europe: Moscow, Russia");
          break;
        case 4:
          System.out.println("Africa: Lagos, Nigeria");
          break;
        case 5:
          System.out.println("Asia: Shanghai, China");
          break;
      }

	}
}
```

13. Add another `case` that will run when the value of `continent` is `6`. When this value is met, print out `Australia: Sydney, Australia`. Make sure the next line exits out of the case.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
          System.out.println("North America: Mexico City, Mexico");
          break;
        case 2:
          System.out.println("South America: Sao Paulo, Brazil");
          break;
        case 3:
          System.out.println("Europe: Moscow, Russia");
          break;
        case 4:
          System.out.println("Africa: Lagos, Nigeria");
          break;
        case 5:
          System.out.println("Asia: Shanghai, China");
          break;
        case 6:
          System.out.println("Australia: Sydney, Australia");
          break;
      }

	}
}
```

14. Add another `case` that will run when the value of `continent` is `7`. When this value is met, print out `Antarctica: McMurdo Station, US`. Make sure the next line exits out of the case.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
          System.out.println("North America: Mexico City, Mexico");
          break;
        case 2:
          System.out.println("South America: Sao Paulo, Brazil");
          break;
        case 3:
          System.out.println("Europe: Moscow, Russia");
          break;
        case 4:
          System.out.println("Africa: Lagos, Nigeria");
          break;
        case 5:
          System.out.println("Asia: Shanghai, China");
          break;
        case 6:
          System.out.println("Australia: Sydney, Australia");
          break;
        case 7:
          System.out.println("Antarctica: McMurdo Station, US");
          break;
      }

	}
}
```

15. Finally, add the `default` case. The `default` case should print out `Undefined continent!` Make sure the next line exits out of the case.

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
      
      int continent = 4;

      switch (continent) {
        case 1:
          System.out.println("North America: Mexico City, Mexico");
          break;
        case 2:
          System.out.println("South America: Sao Paulo, Brazil");
          break;
        case 3:
          System.out.println("Europe: Moscow, Russia");
          break;
        case 4:
          System.out.println("Africa: Lagos, Nigeria");
          break;
        case 5:
          System.out.println("Asia: Shanghai, China");
          break;
        case 6:
          System.out.println("Australia: Sydney, Australia");
          break;
        case 7:
          System.out.println("Antarctica: McMurdo Station, US");
          break;
        default:
          System.out.println("Undefined continent!");
          break;
      }

	}
}
```

16. If the program is written correctly, your output should be `Africa: Lagos, Nigeria`. Great work!

```java
// Continents and their largest cities.

public class Continents {
	public static void main(String[] args) {
	
      int continent = 4;
	
      switch (continent) {
        case 1:
          System.out.println("North America: Mexico City, Mexico");
          break;
        case 2:
          System.out.println("South America: Sao Paulo, Brazil");
          break;
        case 3:
          System.out.println("Europe: Moscow, Russia");
          break;
        case 4:
          System.out.println("Africa: Lagos, Nigeria");
          break;
        case 5:
          System.out.println("Asia: Shanghai, China");
          break;
        case 6:
          System.out.println("Australia: Sydney, Australia");
          break;
        case 7:
          System.out.println("Antarctica: McMurdo Station, US");
          break;
        default:
          System.out.println("Undefined continent!");
          break;
      }
	}
}
```
