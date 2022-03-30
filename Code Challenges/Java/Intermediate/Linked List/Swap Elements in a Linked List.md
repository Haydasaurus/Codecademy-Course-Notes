Swap Elements in a Linked List

# Swap Elements in a Linked List
Given the head of a linked list and two values within the list, create a `swapNodes()` method that swaps the nodes with the given values. Your function should return the same list with the nodes swapped.

For example, if your original linked list was named `demoList` and contained `1 -> 2 -> 3 -> 4 -> 5 -> 6`, `swapNodes(demoList, 2, 5)` should return the list containing `1 -> 5 -> 3 -> 4 -> 2 -> 6`.

For this problem, you’ll be using our custom-built `Node` class. The constructor for the node class is as follows:

```Java
public int data;
public Node next;
 
public Node(int data){
  this.data = data;
  this.next = null;
  }
```

The head of a linked list is a `Node` with some `data` whose `next` value points to the `next` `Node` in the linked list.

Variations of this challenge were reported to have been asked at interviews with Google and Amazon. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge. If you have trouble, try refreshing your knowledge with its [Swapping Elements in a Linked List](https://www.codecademy.com/paths/pass-the-technical-interview-with-java/tracks/linear-data-structures-java/modules/linked-list-practice-java/articles/swapping-elements-in-a-linked-list-java) walkthrough first.

---

```Java
public class SwapNodes {

  public static void main(String[] args) {
    Integer[] testArr = {1, 2, 3, 4, 5, 6};
    Node list = Node.makeLinkedList(testArr);
    swapNodes(list, 2, 5);
  }

  public static Node swapNodes(Node list, int data1, int data2) {
    
  }
}
```