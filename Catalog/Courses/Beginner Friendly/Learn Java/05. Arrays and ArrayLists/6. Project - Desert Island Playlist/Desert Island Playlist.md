Learn Java
# Desert Island Playlist

You’re heading to a desert island, cut off from the world, for the next six months. Luckily, you can bring a playlist of your favorite music ♪♪

Also, this is a chance to put your hard-earned Java skills to the test. Your mission, should you choose to accept it:

Build **Playlist.java** with the best possible playlist of music using a Java `ArrayList`. Choose wisely.

---

## Creating Your Playlist

1. We’ve provided you with a file **Playlist.java**.

-   Since you’re working with `ArrayList`s, import `ArrayList` from `java.util`.
-   Create a `Playlist` class with a `main()` method.

Hint:
```java
import java.util.ArrayList;
 
class Playlist {
 
  public static void main(String[] args) {
 
  }
 
}
```

```java
import java.util.ArrayList;

class Playlist {
  
  public static void main(String[] args) {
    
  }
  
}
```

2. Inside main(), create a new ArrayList called desertIslandPlaylist that can hold String values.

Hint:
```java
ArrayList<String> desertIslandPlaylist = new ArrayList<String>();
```

```java
import java.util.ArrayList;

class Playlist {
  
  public static void main(String[] args) {
    ArrayList<String> desertIslandPlaylist = new ArrayList<String>();
    
  }
  
}
```

3. Time to add songs!

Use `add()` to add several (more than five) of your favorite songs to `desertIslandPlaylist`.

Hint: For example, if you wanted to add `"Sneaker Pimps - Six Underground"`, you could do:
```java
desertIslandPlaylist.add("Sneaker Pimps - Six Underground");
```

```java
import java.util.ArrayList;

class Playlist {
  
  public static void main(String[] args) {
    ArrayList<String> desertIslandPlaylist = new ArrayList<String>();

    desertIslandPlaylist.add("Weezer - Island in the Sun");
    desertIslandPlaylist.add("Zac Brown Band - Island Song");
    desertIslandPlaylist.add("Elton John - Island Girl");
    desertIslandPlaylist.add("The Beach Boys - Kokomo");
    desertIslandPlaylist.add("The Merrymen - Feeling Hot Hot Hot");
    desertIslandPlaylist.add("Ritchie Valens - La Bamba");
    desertIslandPlaylist.add("Jimmy Buffett - Margaritaville");
  }
  
}
```

4. Check out your personally curated selection of music by printing desertIslandPlaylist to the terminal. Then run your code.

Hint: For example to print an `ArrayList` called `detectives`:
```java
System.out.println(detectives);
```

To run your code in the terminal:
```java
java Playlist
```

If nothing prints, check what happens when you compile — you may just have a typo:
```java
javac Playlist.java
```

```java
import java.util.ArrayList;

class Playlist {
  
  public static void main(String[] args) {
    ArrayList<String> desertIslandPlaylist = new ArrayList<String>();

    desertIslandPlaylist.add("Weezer - Island in the Sun");
    desertIslandPlaylist.add("Zac Brown Band - Island Song");
    desertIslandPlaylist.add("Elton John - Island Girl");
    desertIslandPlaylist.add("The Beach Boys - Kokomo");
    desertIslandPlaylist.add("The Merrymen - Feeling Hot Hot Hot");
    desertIslandPlaylist.add("Ritchie Valens - La Bamba");
    desertIslandPlaylist.add("Jimmy Buffett - Margaritaville");

    System.out.println(desertIslandPlaylist);
  }
  
}
```

## Cut It Down

5. Yikes! It turns out you can only bring five songs now… You’ll need to make some cuts.

First, check the number of songs on your playlist using `size()`. Print the number to the terminal.

Hint: For example to print the number of items in an `ArrayList` called `detectives`:
```java
System.out.println(detectives.size());
```

```java
import java.util.ArrayList;

class Playlist {
  
  public static void main(String[] args) {
    ArrayList<String> desertIslandPlaylist = new ArrayList<String>();

    desertIslandPlaylist.add("Weezer - Island in the Sun");
    desertIslandPlaylist.add("Zac Brown Band - Island Song");
    desertIslandPlaylist.add("Elton John - Island Girl");
    desertIslandPlaylist.add("The Beach Boys - Kokomo");
    desertIslandPlaylist.add("The Merrymen - Feeling Hot Hot Hot");
    desertIslandPlaylist.add("Ritchie Valens - La Bamba");
    desertIslandPlaylist.add("Jimmy Buffett - Margaritaville");

    System.out.println(desertIslandPlaylist.size());
  }
  
}
```

6. Now, you’ll need to make some tough decisions. Remove songs from your playlist using remove() until you only have five songs left.

You can check the size of your playlist along the way using `.size()` and print out the playlist to see the current songs remaining.

Hint: For example, to remove `"Gramatik - Good Evening, Mr. Hitchcock"` from `desertIslandPlaylist`:
```java
desertIslandPlaylist.remove("Gramatik - Good Evening, Mr. Hitchcock");
```

```java
import java.util.ArrayList;

class Playlist {
  
  public static void main(String[] args) {
    ArrayList<String> desertIslandPlaylist = new ArrayList<String>();

    desertIslandPlaylist.add("Weezer - Island in the Sun");
    desertIslandPlaylist.add("Zac Brown Band - Island Song");
    desertIslandPlaylist.add("Elton John - Island Girl");
    desertIslandPlaylist.add("The Beach Boys - Kokomo");
    desertIslandPlaylist.add("The Merrymen - Feeling Hot Hot Hot");
    desertIslandPlaylist.add("Ritchie Valens - La Bamba");
    desertIslandPlaylist.add("Jimmy Buffett - Margaritaville");

    desertIslandPlaylist.remove("Elton John - Island Girl");
    desertIslandPlaylist.remove("Jimmy Buffett - Margaritaville");

    System.out.println(desertIslandPlaylist.size());
  }
  
}
```

## Swap Songs

7. You’ve grown a little bored of the playlist order. Fortunately, you can change up the ArrayList. Pick out two songs whose order you’d like to swap.

This part is a bit trickier, so start by reading the steps you’ll take to make the switch:

1.  Get the indices of the songs you want to swap.
2.  Create a temporary variable to store the value of song `a`. (We’ll call the songs `a` and `b` here.)
3.  Rewrite the value at the index of `a` to the value of `b`.
4.  Rewrite the value at the index of `b` to the value of the temporary variable.

Hint: No need to change anything in the code here.

8. Use indexOf() to get the indices of the two songs you want to swap in desertIslandPlaylist. (You can store these as variables or print them out.)

Hint: For example:
```java
int indexA = desertIslandPlaylist.indexOf("Buena Vista Social Club - Murmullo");
int indexB = desertIslandPlaylist.indexOf("A Tribe Called Quest - Electric Relaxation");
```

```java
import java.util.ArrayList;

class Playlist {
  
  public static void main(String[] args) {
    ArrayList<String> desertIslandPlaylist = new ArrayList<String>();

    desertIslandPlaylist.add("Weezer - Island in the Sun");
    desertIslandPlaylist.add("Zac Brown Band - Island Song");
    desertIslandPlaylist.add("Elton John - Island Girl");
    desertIslandPlaylist.add("The Beach Boys - Kokomo");
    desertIslandPlaylist.add("The Merrymen - Feeling Hot Hot Hot");
    desertIslandPlaylist.add("Ritchie Valens - La Bamba");
    desertIslandPlaylist.add("Jimmy Buffett - Margaritaville");

    desertIslandPlaylist.remove("Elton John - Island Girl");
    desertIslandPlaylist.remove("Jimmy Buffett - Margaritaville");

    int IndexA = desertIslandPlaylist.indexOf("Zac Brown Band - Island Song");
    int IndexB = desertIslandPlaylist.indexOf("The Merrymen - Feeling Hot Hot Hot");

    System.out.println(desertIslandPlaylist.size());
  }
  
}
```

9. Create a new String variable called tempA and initialize it with the value of song a.

Hint: For example:
```java
String tempA = "Buena Vista Social Club - Murmullo";
```

```java
import java.util.ArrayList;

class Playlist {
  
  public static void main(String[] args) {
    ArrayList<String> desertIslandPlaylist = new ArrayList<String>();

    desertIslandPlaylist.add("Weezer - Island in the Sun");
    desertIslandPlaylist.add("Zac Brown Band - Island Song");
    desertIslandPlaylist.add("Elton John - Island Girl");
    desertIslandPlaylist.add("The Beach Boys - Kokomo");
    desertIslandPlaylist.add("The Merrymen - Feeling Hot Hot Hot");
    desertIslandPlaylist.add("Ritchie Valens - La Bamba");
    desertIslandPlaylist.add("Jimmy Buffett - Margaritaville");

    desertIslandPlaylist.remove("Elton John - Island Girl");
    desertIslandPlaylist.remove("Jimmy Buffett - Margaritaville");

    int IndexA = desertIslandPlaylist.indexOf("Zac Brown Band - Island Song");
    int IndexB = desertIslandPlaylist.indexOf("The Merrymen - Feeling Hot Hot Hot");

    String tempA = "Zac Brown Band - Island Song";

    System.out.println(desertIslandPlaylist.size());
  }
  
}
```

10. Call set() on desertIslandPlaylist to rewrite the song at the index of a with song b. (You’re adding song b where a was in the playlist.)

You can print the playlist and run the code. Song `b` should appear twice in the playlist now.

Hint: For example:
```java
desertIslandPlaylist.set(indexA, "A Tribe Called Quest - Electric Relaxation");
```

```java
import java.util.ArrayList;

class Playlist {
  
  public static void main(String[] args) {
    ArrayList<String> desertIslandPlaylist = new ArrayList<String>();

    desertIslandPlaylist.add("Weezer - Island in the Sun");
    desertIslandPlaylist.add("Zac Brown Band - Island Song");
    desertIslandPlaylist.add("Elton John - Island Girl");
    desertIslandPlaylist.add("The Beach Boys - Kokomo");
    desertIslandPlaylist.add("The Merrymen - Feeling Hot Hot Hot");
    desertIslandPlaylist.add("Ritchie Valens - La Bamba");
    desertIslandPlaylist.add("Jimmy Buffett - Margaritaville");

    desertIslandPlaylist.remove("Elton John - Island Girl");
    desertIslandPlaylist.remove("Jimmy Buffett - Margaritaville");

    int indexA = desertIslandPlaylist.indexOf("Zac Brown Band - Island Song");
    int indexB = desertIslandPlaylist.indexOf("The Merrymen - Feeling Hot Hot Hot");

    String tempA = "Zac Brown Band - Island Song";

    desertIslandPlaylist.set(indexA, "The Merrymen - Feeling Hot Hot Hot");

    System.out.println(desertIslandPlaylist.size());
  }
  
}
```

11. Ready to complete the swap?

Use `set()` again on `desertIslandPlaylist`. This time, give the original index of song `b` the value of your temporary variable (which is really song `a`). In other words, you’re putting song `a` where song `b` used to be.

Print the final playlist to see the songs swapped from their original positions.

Hint: For example, if `tempA` stores the value of song `a` and `indexB` stores the original index of song `b`:
```java
desertIslandPlaylist.set(indexB, tempA);
```

```java
import java.util.ArrayList;

class Playlist {
  
  public static void main(String[] args) {
    ArrayList<String> desertIslandPlaylist = new ArrayList<String>();

    desertIslandPlaylist.add("Weezer - Island in the Sun");
    desertIslandPlaylist.add("Zac Brown Band - Island Song");
    desertIslandPlaylist.add("Elton John - Island Girl");
    desertIslandPlaylist.add("The Beach Boys - Kokomo");
    desertIslandPlaylist.add("The Merrymen - Feeling Hot Hot Hot");
    desertIslandPlaylist.add("Ritchie Valens - La Bamba");
    desertIslandPlaylist.add("Jimmy Buffett - Margaritaville");

    desertIslandPlaylist.remove("Elton John - Island Girl");
    desertIslandPlaylist.remove("Jimmy Buffett - Margaritaville");

    int indexA = desertIslandPlaylist.indexOf("Zac Brown Band - Island Song");
    int indexB = desertIslandPlaylist.indexOf("The Merrymen - Feeling Hot Hot Hot");

    String tempA = "Zac Brown Band - Island Song";

    desertIslandPlaylist.set(indexA, "The Merrymen - Feeling Hot Hot Hot");
    desertIslandPlaylist.set(indexB, tempA);

    System.out.println(desertIslandPlaylist);
  }
  
}
```

## Remix!

12. Nice work using ArrayList to build your desert island playlist!

Here’s [one possible solution](https://github.com/Codecademy/learn-java/blob/master/5-arrays-arraylists/Playlist.java).

Want to do even more? Check the hint for ideas.

Hint: 
-   Build another desert island playlist for videos, movies, or tv shows.
-   Create a method that shuffles the song order.
-   Reverse the song order.
