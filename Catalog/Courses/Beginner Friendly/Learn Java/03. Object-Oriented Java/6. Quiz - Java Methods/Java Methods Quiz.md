In this method definition, what does `miles` represent?

```java
public void run(int miles) {}
```

a parameter of type int

(It is the `int` input to the `run()` method)

---

Fill in the code that will call the `addSugar()` method with 7 as an input.

```java
public class Coffee {
 
  public Coffee(){
    
  }
 
  public void addSugar(int sugarCubes){
    System.out.println("Added " + sugarCubes + " sugar cubes!");
  }
  
  public static void main(String[] args){
    Coffee myCup = new Coffee()
    [........]
  }
 
}
```

myCup.addSugar(7)

---

An object named `dalmatian` belongs to the Spot class. Which of the following correctly calls the `run` method on `dalmatian`?

dalmation.run();

(The object is `dalmatian`, and the method `run()` is being called on it)

---

Which line of code is **NOT** an example of calling a method?

int sugarCubes = 7;

(This line of code represents a variable being declared and initialized, not a method being called)

---

When defining a method, the `void` keyword specifies which of the following?

The method does not return a value

(`void` means that nothing is returned from the method call)

---

Which method signature would make a method that returns an `int` and takes in a `String`?

public int countLetters(String message)

(The return type is `int` and the input is of type `String`)

---

Is there an error that will prevent this code from running?

```java
class Coffee{
 
  public Coffee(){
  }
 
  public void stir(){
    String stirring = "Stirring the coffee!";
  }
  
  public static void main(String[] args){
    Coffee myCup = new Coffee();
    myCup.stir();
    System.out.println(stirring);
  }
 
 
}
```

Yes! The variable `stirring` cannot be accessed in the `main()` method.

(`stirring` only exists within the `stir()` method)