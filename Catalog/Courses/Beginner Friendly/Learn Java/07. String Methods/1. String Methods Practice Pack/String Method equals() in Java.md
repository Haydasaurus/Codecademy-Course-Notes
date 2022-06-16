# String Method equals() in Java

```java
String s1 = "Hello";
String s2 = "World";
 
System.out.println(s1.equals("Hello"));
// prints true
 
System.out.println(s2.equals("Hello"));
// prints false 
 
System.out.println(s2.equalsIgnoreCase("world"));
// prints true 
```

In Java, the `equals()` string method tests for equality between two `String`s.

`equals()` compares the contents of each `String`. If all of the characters between the two match, the method returns `true`. If any of the characters do not match, it returns `false`.

Additionally, if you want to compare two strings without considering upper/lower cases, you can use `.equalsIgnoreCase()`.