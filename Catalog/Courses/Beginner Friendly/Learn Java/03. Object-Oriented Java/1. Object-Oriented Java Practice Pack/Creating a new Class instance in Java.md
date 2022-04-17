# Creating a new Class instance in Java

```java
public class Person {  
	int age;  
	// Constructor:  public Person(int a) {    
		age = a;  
}    
	
	public static void main(String [] args) {    
		// Here, we create a new instance of the Person class:    
		Person p = new Person(20);    
		System.out.println("Age is " + p.age); // Prints: Age is 20  
	}
}
```

In Java, we use the `new` keyword followed by a call to the class constructor in order to create a new _instance_ of a class.

The constructor can be used to provide initial values to instance fields.