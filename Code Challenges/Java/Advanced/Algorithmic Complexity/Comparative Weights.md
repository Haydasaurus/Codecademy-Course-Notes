Comparative Weights

# Comparative Weights
Suppose you had `n` basketballs, all of them seemingly identical. You are given a balance scale and told that one of the `n` balls is slightly heavier than the others. What’s the fewest number of times you have to use the scale to find the outlier? You can assume that the scale is very large and able to fit all `n` balls on _each_ side. Write a `scaleOfTruthN()` method that takes in the number of basketballs and determines the minimum number of weighs that you’ll need to find the outlier`.

For example, if you have 3 balls, you can compare 2 of them to see if they are of equal weight. If they are, then you know the ball that you didn’t weigh is the outlier. On the other hand, if they aren’t of equal weight, then the heavier ball is the outlier. Therefore, `scaleOfTruthN(3)` should return `1`.

This challenge was reported to have been asked in interviews at many top companies, including Microsoft. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge with its [Algorithmic Complexity](https://www.codecademy.com/paths/pass-the-technical-interview-with-java/tracks/algorithmic-concepts-java/modules/algorithmic-complexity-java/articles/cspath-why-asymptotic-notation) content.

---

```Java
public class ComparativeWeights {
  public static void main(String[] args) {
    scaleOfTruthN(3);
  }

  public static int scaleOfTruthN(int n) {
    
  }
}
```