What does the following code do?
```java
System.out.println(8 <= 8);
```

Prints `true`

(8 is less than or equal to 8, so the code inside the `System.out.println()` evaluates to `true`)

---

The expression `5 != 6` will evaluate to what value?
true

(Since `5` is not equal to `6`, this line evaluates to `true`)

---

Are there any errors in this Java statement?

```
int status = 7 < 8;
```

Yes, `int` should be `boolean`

(The expression `7 < 8` will evaluate to `true`, which must be stored as a `boolean`, not an `int`)

---

True or False: The value of a variable declared with the `final` keyword can be changed after its initial declaration.
False

(If a variable is declared with the `final` keyword, its value cannot be changed)

---

To what value does the following string concatenation evaluate?
```java
"It's " + 5 + "pm"
```

"It's 5pm"

(The `+` will turn `5` into a String and then concatenate it)

---

What will the following program output?
```java
int num = 12;
num *= 2;
num -= 4;
num++;
System.out.println(num);
```

21

(`num` was declared with a value of `12`. Then, `num` was multiplied by `2`. Next, `4` was subtracted from `num`. Finally, `num` was increased by `1`)

---

What is the best way to tell if the following two Strings are equal?
```java
String username1 = "teracoder";String username2 = "gigacoder";
```

username1.equals(username2)

(This command will compare the usernames against each other)

---

Which operator can be used to concatenate two Strings?

+

(The plus sign will create a new combined String from two Strings)

---

After the following code is run, what value will the variable `endpoint` be assigned to?
```java
int endpoint = 11 % 3;
```

2

(The modulo operator `%` returns the remainder. The remainder of `11` divided by `3` is `2`)

---

How could we get a result of `10`, given the following variable?
```java
double a = 2;
```

a * 5

(`2` multiplied by `5` will give us `10`)