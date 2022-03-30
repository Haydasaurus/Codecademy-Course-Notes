Max Product Finder

# Max Product Finder
Create a `maxProductFinderK()` method that takes in a list of numbers and an integer `k`, and returns the largest product that can be attained from any `k` integers in the list. You may presume that the length of the list of integers is greater than or equal to `k`.

For example, calling `maxProductFinderK()` on `([-8, 6, -7, 3, 2, 1, -9], 2)` should return `72`, and calling `maxProductFinderK()` on `([-8, 6, -7, 3, 2, 1, -9], 3)` should return `432`.

This challenge was reported to have been asked at interviews with Google. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge with its [Heaps](https://www.codecademy.com/paths/pass-the-technical-interview-with-java/tracks/nonlinear-data-structures-java/modules/heaps-java/lessons/conceptual-heaps/exercises/conceptual-heaps-heapify-down) content.

---

```Java
import java.util.Arrays;
public class MaxProductFinder {
  public static void main(String[] args) {
    int[] arr = new int[]{-8, 6, -7, 3, 2, 1, -9};
    int result = maxProductFinderK(arr, 3);
    System.out.println(result);
  }

  public static int maxProductFinderK(int[] array, int k) {
    // Write your code here
  }
}
```