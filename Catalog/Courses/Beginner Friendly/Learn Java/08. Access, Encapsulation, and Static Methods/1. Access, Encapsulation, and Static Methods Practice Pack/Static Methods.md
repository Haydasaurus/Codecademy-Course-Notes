# Static Methods

```java
// static method
public static int getTotal(int a, int b) {
  return a + b;
}
 
public static void main(String[] args) {
  int x = 3;
  int y = 2;
  System.out.println(getTotal(x,y)); // Prints: 5
}
```

Static methods are methods that can be called within a program without creating an object of the class.