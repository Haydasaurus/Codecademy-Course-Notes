# Strings

```java
// Creating a String variable
String name = "Bob";

// The following will print "false" because strings are case-sensitive
System.out.println(name.equals("bob"));
```

A String in Java is a Object that holds multiple characters. It is not a primitive datatype.

A String can be created by placing characters between a pair of double quotes (`"`).

To compare Strings, the `equals()` method must be used instead of the primitive equality comparator `==`.