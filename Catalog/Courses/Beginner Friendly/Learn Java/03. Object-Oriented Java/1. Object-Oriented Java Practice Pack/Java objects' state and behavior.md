# Java objects’ state and behavior

```java
public class Person {  
	// state of an object  
	int age;  
	String name;    
	
	// behavior of an object  
	public void set_value() {    
		age = 20;    
		name = "Robin";  
	}  
	public void get_value() {    
		System.out.println("Age is " + age);    
		System.out.println("Name is " + name);  
	}    
	
	// main method  
	public static void main(String [] args) {    
		// creates a new Person object    
		Person p = new Person();         
		
		// changes state through behavior    
		p.set_value();  
	}
}
```

In Java, instances of a class are known as objects. Every object has state and behavior in the form of instance fields and methods respectively.