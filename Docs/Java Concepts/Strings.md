# Strings
A `String` in Java is an object that holds a sequence of characters contained within a pair of double quotes (`"`). It is not a primitive datatype.

Java strings provide a way to store something like a word, sentence, or whole paragraph. They can be any length and can contain letters, numbers, symbols, and spaces.

```Java
// Creating a String variable
String name = "Codecademy";

// Creating another String variable
String address = "575 Broadway #5, New York, NY 10012";
```

To compare `String`s, the `.equals()` method must be used instead of the primitive equality comparator `==`. `.equals()` will compare the values of the strings, while `==` compares the references (location in memory) of the strings.

```Java
String name = "Bob";

// The following will print "false" because strings are case-sensitive
System.out.println(name.equals("bob"));
```

---

## Strings
[.charAt()](https://www.codecademy.com/resources/docs/java/strings/charAt)
Returns the character at the given index in the string.

[.codePointAt()](https://www.codecademy.com/resources/docs/java/strings/codePointAt)
Returns the Unicode value at the given index in the string.

[.codePointBefore()](https://www.codecademy.com/resources/docs/java/strings/codePointBefore)
Returns the Unicode value before the given index in the string.

[.codePointCount()](https://www.codecademy.com/resources/docs/java/strings/codePointCount)
Returns the number of Unicode values in specified range of a string.

[.compareTo()](https://www.codecademy.com/resources/docs/java/strings/compareTo)
Compares two strings lexicographically based on the Unicode value of each character in the string.

[.compareToIgnoreCase()](https://www.codecademy.com/resources/docs/java/strings/compareToIgnoreCase)
Compares two strings lexicographically based on the Unicode value of each character in the string while ignoring lower case and upper case differences.

[.concat()](https://www.codecademy.com/resources/docs/java/strings/concat)
Returns a string that is the concatenation of the given strings.

[.contains()](https://www.codecademy.com/resources/docs/java/strings/contains)
Returns true if a sequence of characters exists in a given string, otherwise false.

[.contentEquals()](https://www.codecademy.com/resources/docs/java/strings/contentEquals)
Returns true if the sequence of characters in the string is equal to the content of the specified string. If not, returns false.

[.copyValueOf()](https://www.codecademy.com/resources/docs/java/strings/copyValueOf)
Returns a string with characters copied from an array.