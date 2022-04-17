# Java instance

```java
public class Person {  
	int age;  
	String name;    
	
	// Constructor method  
	public Person(int age, String name) {    
		this.age = age;    
		this.name = name;  
	}    
	
	public static void main(String[] args) {    
		Person Bob = new Person(31, "Bob");    
		Person Alice = new Person(27, "Alice");  
	}
}
```

Java instances are objects that are based on classes. For example, `Bob` may be an instance of the class `Person`.

Every instance has access to its own set of variables which are known as _instance fields_, which are variables declared within the scope of the instance. Values for instance fields are assigned within the constructor method.