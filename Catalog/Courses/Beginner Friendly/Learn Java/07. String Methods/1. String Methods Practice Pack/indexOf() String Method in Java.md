# indexOf() String Method in Java

```java
String str = "Hello World!";
 
System.out.println(str.indexOf("l"));
// prints 2
 
System.out.println(str.indexOf("Wor"));
// prints 6
 
System.out.println(str.indexOf("z"));
// prints -1
```

In Java, the `indexOf()` string method returns the first occurrence of a character or a substring in a `String`. The character/substring that you want to find the index of goes inside of the `()`.

If `indexOf()` cannot find the character or substring, it will return -1.