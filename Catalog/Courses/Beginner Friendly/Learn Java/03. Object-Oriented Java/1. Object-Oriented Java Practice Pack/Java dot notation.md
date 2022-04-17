# Java dot notation

```java
public class Person {  
	int age;    
	
	public static void main(String [] args) {    
	Person p = new Person();        
	
	// here we use dot notation to set age    
	p.age = 20;         
	
	// here we use dot notation to access age and print    
	System.out.println("Age is " + p.age);    
	// Output: Age is 20  
	}
}
```

In Java programming language, we use `.` to access the variables and methods of an object or a Class.

This is known as _dot notation_ and the structure looks like this-

`instanceOrClassName.fieldOrMethodName`