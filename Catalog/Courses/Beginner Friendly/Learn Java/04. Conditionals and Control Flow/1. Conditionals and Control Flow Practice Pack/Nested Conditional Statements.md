# Nested Conditional Statements
```java
boolean studied = true;
boolean wellRested = true;
 
if (wellRested) {
  System.out.println("Best of luck today!");  
  if (studied) {
    System.out.println("You are prepared for your exam!");
  } else {
    System.out.println("Study before your exam!");
  }
}
 
// Prints: Best of luck today!
// Prints: You are prepared for your exam!
```

A nested conditional statement is a conditional statement nested inside of another conditional statement. The outer conditional statement is evaluated first; if the condition is `true`, then the nested conditional statement will be evaluated.