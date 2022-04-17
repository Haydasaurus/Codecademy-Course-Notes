# Reference Data Types

```java
public class Cat {  
	public Cat() {    
		// instructions for creating a Cat instance  
	}

	public static void main(String[] args) {    
		// garfield is declared with reference data type `Cat`     
		Cat garfield = new Cat();    
		System.out.println(garfield); // Prints: Cat@76ed5528  
	}
}
```

A variable with a reference data type has a value that references the memory address of an instance. During variable declaration, the class name is used as the variable’s type.