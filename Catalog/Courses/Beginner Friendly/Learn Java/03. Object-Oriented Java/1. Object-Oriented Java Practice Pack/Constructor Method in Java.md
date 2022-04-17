# Constructor Method in Java

```java
public class Maths {  
	public Maths() {    
		System.out.println("I am constructor");  
	}  
	public static void main(String [] args) {    
		System.out.println("I am main");    
		Maths obj1 = new Maths();  
	}
}
```

Java classes contain a _constructor_ method which is used to create instances of the class.

The constructor is named after the class. If no constructor is defined, a default empty constructor is used.