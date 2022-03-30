Maximize Stock Trading Profit

# Maximize Stock Trading Profit
Given the daily values of a stock, create a function called `maxProfitDays()` that, given an array of integers, will return the index value of the two elements that represent the day on which one should have bought a share and the day on which one should have sold a share based on the max profit.

An array of integers will represent the stock price at the beginning or “opening bell” of each day for a week. You are required to buy and sell only once. You also must buy a stock before selling it.

For example, given the array `{7, 11, 60, 25, 150, 75, 31, 120}`, you can assume that index 0 represents day 0 and index 7 represents day 7. In this case, purchasing on day 1 and selling on day 4 would yield the most profit. If we were to call `maxProfitDays()` with an array containing the values `{17, 11, 60, 25, 150, 75, 31, 120}` as the argument, the function would return `{1, 4}`.

This challenge and variations of it were reported to have been asked at interviews with Google. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge there first.

---

```Java
import java.util.*;

public class MaxProfitDays {
  public static void main(String[] args) {
    int[] stockPrices = {17, 11, 60, 25, 150, 75, 31, 120};
    int[] maxProfitDays = (maxProfitDays(stockPrices));
    System.out.println(maxProfitDays[0]);
    System.out.println(maxProfitDays[1]);
  }

  public static int[] maxProfitDays(int[] stockPrices) {
    // Add your code here

    
  }

}
```