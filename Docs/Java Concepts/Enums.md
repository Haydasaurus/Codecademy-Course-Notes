# Enums
Enumeration (enum) is a special user defined type where we specify a set of values for a variable and the variable can only take one out of a small set of possible values.

The keyword `enum` is used to define an enumeration.

An `enum` can contain constants, methods, etc.

---

## Syntax
Here’s the basic syntax for creating an `enum`:

```Java
public enum name {
  constant1,
  constant2,
  ...
}
```

Here’s an `enum` with compass directions:

```Java
public enum Direction {
  NORTH, SOUTH, EAST, WEST
}
```

-   `Direction.NORTH` will have a value of 0.
-   `Direction.SOUTH` will have a value of 1.
-   `Direction.EAST` will have a value of 2.
-   `Direction.WEST` will have a value of 3.

## Example

```Java
public enum Day {
  SUN, MON, TUE, WED,
  THU, FRI, SAT
}
```

-   `Day.SUN` will have a value of 0.
-   `Day.MON` will have a value of 1.
-   `Day.TUE` will have a value of 2.
-   `Day.WED` will have a value of 3.
-   `Day.THU` will have a value of 4.
-   `Day.FRI` will have a value of 5.
-   `Day.SAT` will have a value of 6.

To access one of the values:

```Java
Day day = Day.MON;
```