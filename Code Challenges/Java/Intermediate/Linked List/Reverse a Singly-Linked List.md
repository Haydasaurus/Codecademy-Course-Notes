Reverse a Singly-Linked List

# Reverse a Singly-Linked List
Given the head of a linked list, write a method named `reverseLinkedList(linkedList)` that reverses that linked list. Your method should return the head of a new linked list where the values are in reverse order of the original linked list.

For example, if your original linked list was `4 -> 8 -> 15 -> None`, your method should return the head of the linked list `15 -> 8 -> 4 -> None`.

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

This challenge was reported to have been asked at interviews with Google and Amazon. If you’ve covered the material in [Pass the Technical Interview with Java](https://www.codecademy.com/learn/paths/pass-the-technical-interview-with-java) or an equivalent, you should be able to solve this challenge.

---

```Java
public class Reverse{

  public static Node reverseLinkedList(Node linkedList){
    // Write your code here
  }

  public static void main(String[] args){
      Integer[] testArr = {4, 8, 15};
      Node testNode = Node.makeLinkedList(testArr);
      System.out.println("Original Linked List");
      testNode.print();
      Node reversed = Reverse.reverseLinkedList(testNode); 
      System.out.println("Reversed Linked List");
      reversed.print();
    }
}
```