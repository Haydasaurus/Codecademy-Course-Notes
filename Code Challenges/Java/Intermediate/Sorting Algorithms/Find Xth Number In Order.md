Find Xth Number In Order

# GetX
Write a function, `getX`, that given an int `x` and a integer array `num`, returns the Xth number if the list was in sorted order. In other words, the Xth smallest number.

Function Name: `getX`

Input: An integer, `x`, and an unsorted list of integers `nums` that aren’t necessarily distinct

Output: The integer corresponding to the Xth number in the sorted list

Example:

```
getX(2, [5, 10, -3, -3, 7, 9]) => -3
```

The second number in order is -3.

```
getX(4, [5, 10, -3 , -3, 7, 9]) => 7
```

The fourth number in order is 7.

Note that this assumes the first number is position 1, not 0.

This challenge was reported to have been asked in interviews at many top companies, including Amazon. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge.

---

```Java
class FindXInOrder {

  public static int getX(int x, int[] nums) {
    // Work on your code here

  }
  
  public static void main(String[] args) {
    int nums[] = new int[]{ 12, 3, 5, 7, 4, 19, 26};
    int x = 3;
    System.out.print(getX(3, nums));
  }
}
```