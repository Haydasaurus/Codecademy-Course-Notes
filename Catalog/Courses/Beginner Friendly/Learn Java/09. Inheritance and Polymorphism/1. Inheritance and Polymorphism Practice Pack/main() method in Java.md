# Main() method in Java

```java
// Shape.java file 
class Shape {
  public static void main(String[] args) {
    Square sq = new Square();
  }
}
 
// Square.java file 
class Square extends Shape {
  
}
```

In simple Java programs, you may work with just one class and one file. However, as your programs become more complex you will work with multiple classes, each of which requires its own file. Only one of these files in the Java package requires a `main()` method, and this is the file that will be run in the package.

For example, say we have two files in our Java package for two different classes:

-   `Shape`, the parent class.
-   `Square`, the child class.

If the Java file containing our `Shape` class is the only one with a `main()` method, this is the file that will be run for our Java package.