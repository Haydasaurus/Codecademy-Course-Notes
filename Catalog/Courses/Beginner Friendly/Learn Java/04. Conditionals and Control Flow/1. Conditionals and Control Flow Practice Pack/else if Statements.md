# else if Statements

```java
int testScore = 76;
char grade;
 
if (testScore >= 90) {
  grade = 'A';
} else if (testScore >= 80) {
  grade = 'B';
} else if (testScore >= 70) {
  grade = 'C';
} else if (testScore >= 60) {
  grade = 'D';
} else {
  grade = 'F';
}
 
System.out.println("Grade: " + grade); // Prints: C
```

`else`-`if` statements can be chained together to check multiple conditions. Once a condition is `true`, a code block will be executed and the conditional statement will be exited.

There can be multiple `else`-`if` statements in a single conditional statement.