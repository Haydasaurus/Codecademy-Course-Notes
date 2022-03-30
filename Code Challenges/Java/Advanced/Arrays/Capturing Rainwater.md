Capturing Rainwater

# Capturing Rainwater
Create a `capturingRainwater()` method that takes in an array of heights, and returns the amount of rainwater that could be contained in that array.

For example, the array `[4, 2, 1, 3, 0, 1, 2]` can be represented in the following histogram: 

![](https://i.imgur.com/VuTjjax.jpg)

As you can see, there are 6 units of water that can be contained, so calling `capturing_rainwater()` on the array `[4, 2, 1, 3, 0, 1, 2]` should return `6`.

This challenge was reported to have been asked at interviews with many top companies, including Amazon and Microsoft. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge with its [Capturing Rainwater](https://www.codecademy.com/paths/pass-the-technical-interview-with-java/tracks/java-interview-prep-and-algorithms-practice/modules/java-interview-problems/articles/capturing-rainwater-in-java) walkthrough.

---

```Java
public class CapturingRainwater {
  public static void main(String[] args) {
    int[] heights = new int[] {4, 2, 1, 3, 0, 1, 2};
    System.out.println(capturingRainwater(heights));
  }

  public static int capturingRainwater(int[] heights) {
    // Write your code here
  }
}
```