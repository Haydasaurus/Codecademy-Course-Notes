# Conditional Operators - Order of Evaluation

```java
boolean foo = true && (!false || true); // true
/* 
(!false || true) is evaluated first because it is contained within parentheses. 
 
Then !false is evaluated as true because it uses the NOT operator. 
 
Next, (true || true) is evaluation as true. 
 
Finally, true && true is evaluated as true meaning foo is true. */
```

If an expression contains multiple conditional operators, the order of evaluation is as follows: 

Expressions in parentheses -> NOT -> AND -> OR.