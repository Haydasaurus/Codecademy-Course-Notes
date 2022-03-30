Product of Everything Else

# Product of Everything Else
Create a `productOfTheOthers()` method that takes in an array of integers and replaces each number in the array with the product of all the numbers in the array except the number at the index itself.

For example, calling `productOfTheOthers()` on `[1, 2, 3, 4, 5]` should return `[120, 60, 40, 30, 24]`, and calling it on `[5, 5, 5]` should return `[25, 25, 25]`.

This challenge was reported to have been asked at interviews with Google. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge with its [Algorithmic Complexity](https://www.codecademy.com/paths/pass-the-technical-interview-with-java/tracks/algorithmic-concepts-java/modules/algorithmic-complexity-java/articles/cspath-why-asymptotic-notation) content.

---

```Java
public class ProductOfOthers {
  public static void main(String[] args) {
    // Calling your function on an example
    int[] testArray = new int[]{1, 2, 3, 4, 5};
    int[] outputArray = productOfTheOthers(testArray);
    for (int i = 0; i < testArray.length; i++) {
      System.out.println(outputArray[i]);
    }
  }

  public static int[] productOfTheOthers(int[] array) {
    // Write your code here
  }
}
```