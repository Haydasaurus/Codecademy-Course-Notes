How would you access the element `"Gorgeous"` of the following array?

```java
String[] tsSongs = {"Delicate", "Gorgeous", "All Too Well", "Hey Stephen"};
```

`tsSongs[1]`

(`"Gorgeous"` is at index 1 of the array.)

---

What type is the following object?

```
{4, 5, 2, 1, 7}
```

`int[]`

(This is an array holding integer values.)

---

Fill in the code to print the array so that its actual values display, instead of the memory address.

```java
import java.util.Arrays;
 
class Restaurant{
 
  public void printSpecials(){
    String[] specials = {"Chicken Mountain", "Lake of Broth", "Wishbone Tower"};
    System.out.println(________);
  }
  
  public static void main(String[] args){
    Restaurant chickenKitchen = new Restaurant();
    chickenKitchen.printSpecials();
  }
}
```

`Arrays.toString(specials)`

---

What property holds the number of elements in an array?

`.length`

(You can access `.length` on an array to get the number of elements it holds.)

---

Fill in the code to set `taxRates` to be an empty array of size 10, holding doubles.

```java
class Tax {
 
  public static void main(String[] args){
    double[] taxRates = ________;
  }
}
```

`new double[10]`

---

What would be printed out by the following code if a user ran the command:

```
java Restaurant 6 vegetarians
```

```java
class Restaurant{
  
  public static void main(String[] args){
    System.out.println("Table for a party of " + args[0]);
    if(args[1].equals("vegetarians")){
      // Do something for vegetarian eaters
    }
    else {
      // Do something for meat eaters
    }
  }
}
```

`Table for a party of 6`

(`args[0]` is the first element in the arguments array.)