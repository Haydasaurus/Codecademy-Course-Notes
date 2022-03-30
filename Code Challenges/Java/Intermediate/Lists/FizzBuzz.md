FizzBuzz

# FizzBuzz
Write a `fizzbuzz()` method that takes in a number, `n`, and returns an `ArrayList` of the numbers from 1 to `n`. For multiples of three, use `"Fizz"` instead of the number, and for the multiples of five, use `"Buzz"`. For numbers that are multiples of both three and five, use `"FizzBuzz"` (capitalization matters).

For example, `fizzbuzz(16)` should return `[1, 2, "Fizz", 4, "Buzz", "Fizz", 7, 8, "Fizz", "Buzz", 11, "Fizz", 13, 14, "FizzBuzz", 16]`.

This challenge was reported to have been asked at interviews with many top companies, including Google. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge there first.

---

```Java
import java.util.*;

public class FizzBuzz {
  public static void main(String[] args) {
    System.out.println(fizzbuzz(16));
  }

  public static ArrayList fizzbuzz(int n) 
  {
    // Write your code here
  }
}
```