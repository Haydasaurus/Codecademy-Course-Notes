Stairmaster

# Stairmaster
Write a function, `stairmaster(n)`, that will compute the number of ways to climb a flight of `n` steps, taking `1`, `2`, or `3` steps at a time.

Take the example of climbing `n = 4` steps. There are seven different ways one can climb four stairs using 1, 2, or 3 steps at a time: [1,1,1,1] [2,1,1] [1,2,1] [1,1,2] [2,2] [1,3] [3,1].

Make sure to find all permutations, not combinations, as the order matters. Climbing one step then two steps is different from climbing two steps then one step.

This challenge and variations of it were reported to have been asked at interviews with Google. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge there first.

---

```Java
import java.util.Arrays;

public class Stairmaster {
    public static int stairmaster(int n) {
      
    }
     
    public static void main(String args[]) {
      System.out.println(stairmaster(4));
    }
}
```