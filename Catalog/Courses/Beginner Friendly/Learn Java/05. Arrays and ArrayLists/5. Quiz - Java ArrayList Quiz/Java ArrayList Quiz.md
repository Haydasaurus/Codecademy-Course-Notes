What does the following code print?

```java
import java.util.ArrayList;
 
public class RatingMachine {
  
  public static void main(String[] args) {
    
    ArrayList<Double> ratings = new ArrayList<Double>();
    
    ratings.add(1.7);
    ratings.add(2.5);
    ratings.add(3.5);
    ratings.remove(1);
    
    System.out.println(ratings.get(1));
    
  }
}
```

`3.5`

(After `2.5` is removed, `3.5` becomes the element at position 1 of the `ArrayList`.)

---

What will the `ArrayList` `usernames` hold after this code runs?

```java
import java.util.ArrayList;
 
public class LogIn {
  
  public static void main(String[] args) {
    
    ArrayList<String> usernames = new ArrayList<String>();
    
    usernames.add("teraCoder");
    usernames.add("javaKnight");
    
  }
}
```

`["terraCoder", "javaKnight"]`

(Both elements will be held in order.)

---

What will the following code print?

```java
import java.util.ArrayList;
 
public class Temperatures {
 
  public static void main(String[] args) {
    
    ArrayList<Integer> temperatures = new ArrayList<Integer>();
    
    temperatures.add(78);
    temperatures.add(67);
    temperatures.add(89);
    temperatures.add(94);
    
    System.out.println(temperatures.get(2));
    
  }
}
```

`89`

(`89` is the element at index `2` of the `temperatures` `ArrayList`.)

---

What method can you use to find the position of a specific element in an `ArrayList`?

`indexOf()`

(When you pass an element into `indexOf()`, it will return the position of that element in the `ArrayList`.)

---

What will the `ArrayList` `kidsMovies` hold after the code is run?

```java
import java.util.ArrayList;
 
public class Rankings {
  
  public static void main(String[] args) {
    
    ArrayList<String> kidsMovies = new ArrayList<String>();
    
    kidsMovies.add("Moana");
    kidsMovies.add("Up");
    kidsMovies.add("WALL-E");
    
    kidsMovies.set(0, "Babe");
    
  }
}
```

`["Babe", "Up", "WALL-E"]`

(`"Babe"` replaces the value that was at position `0` of the `ArrayList`.)

---

Fill in the code to print out how many elements are stored in the `grades` `ArrayList`.

```java
import java.util.ArrayList;
 
public class TemperaturesC {
  
  public static void main(String[] args) {
    
    ArrayList<Char> grades = new ArrayList<Char>();
    grades.add('B');
    grades.add('B');
    grades.add('D');
    
    System.out.println(________);
 
  }
}
```

`grades.size()`

---

Fill in the blank to declare the `ArrayList` to hold the correct type.

```java
import java.util.ArrayList;
 
public class Gradebook{
  
  public static void main(String[] args){
    
    ArrayList _______ quizGrades;
    // we will add the values 96, 87, and 46 later in the method
    
  }
}
```

`<Integer>`