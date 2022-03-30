Find the Missing Numbers

# Find the Missing Number
You have a bag containing tiles with numbers `[1, 2, 3, …, n]` written on them. Each number appears exactly once, so there are `n` tiles and `n` numbers. Now, without looking, `k` number tiles are randomly picked out of the bag and discarded. Create a `missingNos()` function that takes in a list and `k`, and returns the missing numbers in ascending order (from smallest to greatest).

For example, calling `missingNos()` with `([1, 2, 4, 5, 6, 7, 8, 10], 2)` should return `[3, 9]`.

This challenge was reported to have been asked at interviews with Twitter. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge there first.

---

```Java
public class MissingNumber {
  public static void main(String[] args) {
    int[] answer = missingNos(new int[]{1, 2, 4, 5, 6, 7, 8, 10}, 2);
    System.out.println(answer[0]);
    System.out.println(answer[1]);
  }

  public static int[] missingNos(int[] array, int k) {
    // Write your code here
  }
}
```