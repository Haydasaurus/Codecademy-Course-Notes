The following Boolean expression will be evaluated to what value?

```java
!(false) && (5 > 4)
```

true

(`!(false)` returns `true` and `( 5 > 4 )` is also true. `true && true` is `true`!)

---

The `break` keyword is important in a `switch` statement due to which of the following?

Without `break`, Java will continue to check other cases in the `switch` statement,

---

If multiple conditional operators are placed in a single expression, which operator gets evaluated first?

The `NOT` operator - `!`

(The order of evaluation is: the NOT operator (`!`) -> the AND operator (`&&`) -> the OR operator (`||`))

---

The OR logical operator is represented in Java by which operator?

`||`

---

What will the following code print?

```java
int choice = 5;
 
switch (choice) {
  case 4: 
    System.out.println("Jo Fraizer");
    break;
  case 5: 
    System.out.println("Laila A. Lee");
    break;
  case 6: 
    System.out.println("Hall E. Home");
    break;
  default: 
    System.out.println(200);
}
```

`Laila A. Lee`

(`choice` is `5` so `case 5`‘s code block will run.)

---

What will the following code print?

```java
if (5 > 6) {
    System.out.println("C. Senor");
} else if (6 < 5) {
    System.out.println("Sue Yu");
} else {
    System.out.println("Jim Sox");
}
```

`Jim Sox`

(`5 > 6` returns `false` and also `6 < 5` also returns `false`. So the `else` statement is ran.)

---

The AND logical operator is represented in Java by which operator?

`&&`