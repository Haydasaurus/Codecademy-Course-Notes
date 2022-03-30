Calculate the Mean and Mode

# Calculate the Mean and Mode
Create a `statsFinder()` method that takes in a list of numbers and returns a list containing the mean and mode, in that order. As a reminder, the mean is the average of the values and the mode is the most occurring value. If there are multiple modes, return the mode that occurs first. Make sure that you write your functions and find these answers from scratch – don’t use imported tools!

For example, calling `statsFinder()` on the array `[500, 400, 400, 375, 300, 350, 325, 300]` should return `[368.75, 400]`.

Variations of this challenge were reported to have been asked at interviews with Amazon. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge with its [Algorithmic Complexity](https://www.codecademy.com/paths/pass-the-technical-interview-with-java/tracks/algorithmic-concepts-java/modules/algorithmic-complexity-java/articles/cspath-why-asymptotic-notation) content.

---

```Java
public class StatsFinder {
  public static void main(String[] args) {
    double[] ans = statsFinder(new int[]{500, 400, 400, 375, 300, 350, 325, 300});
    System.out.println(ans[0]);
    System.out.println(ans[1]);
  }

  public static double[] statsFinder(int[] array) {
    // Write your code here
  }
}
```