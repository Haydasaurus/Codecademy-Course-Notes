Top Score Sorter

# Top Score Sorter
Write a `scoreSorter()` method that will take a list of unsorted scores along with the highest possible score. It should return a sorted list of all of the scores, in descending order from high to low. You are expected to create and implement your own sorting algorithm for this challenge.

For example, calling `scoreSorter()` on `([1, 2, 3, 9999, 13], 10000)` should return `[9999, 13, 3, 2, 1]`.

This challenge was reported to have been asked at interviews with Amazon. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge with its [Sorting Algorithms](https://www.codecademy.com/paths/pass-the-technical-interview-with-java/tracks/sorting-algorithms-java/modules/bubble-sort-java/informationals/sorting-algorithms-java) content.

---

```Java
import java.util.*;

public class ScoreSorter {
  public static void main(String[] args) {
    int[] answer = scoreSorter(new int[]{1, 2, 3, 9999, 13}, 10000);
    for (int i = 0; i < answer.length; i++) {
      System.out.println(answer[i]);
    }
  }

  public static int[] scoreSorter(int[] array, int topScore) {
    // Write your code here
  }
}
```