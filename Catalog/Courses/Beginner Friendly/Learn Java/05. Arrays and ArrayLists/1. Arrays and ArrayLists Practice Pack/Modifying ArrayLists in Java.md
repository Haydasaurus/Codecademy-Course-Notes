# Modifying ArrayLists in Java

```java
import java.util.ArrayList;
 
public class Students {
  public static void main(String[] args) {
    
     // create an ArrayList called studentList, which initially holds []
        ArrayList<String> studentList = new ArrayList<String>();
    
    // add students to the ArrayList
    studentList.add("John");
    studentList.add("Lily");
    studentList.add("Samantha");
    studentList.add("Tony");
    
    // remove John from the ArrayList, then Lily
    studentList.remove(0);
    studentList.remove("Lily");
    
    // studentList now holds [Samantha, Tony]
    
    System.out.println(studentList);
  }
}
```

An `ArrayList` can easily be modified using built in methods.

To add elements to an `ArrayList`, you use the `add()` method. The element that you want to add goes inside of the `()`.

To remove elements from an `ArrayList`, you use the `remove()` method. Inside the `()` you can specify the index of the element that you want to remove. Alternatively, you can specify directly the element that you want to remove.