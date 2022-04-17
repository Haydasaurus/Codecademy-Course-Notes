# Constructor Signatures

```java
// The signature is `Cat(String furLength, boolean hasClaws)`.
public class Cat {  
	String furType;  
	boolean containsClaws;   
	
	public Cat(String furLength, boolean hasClaws) {    
		furType = furLength;    
		containsClaws = hasClaws;  
	}  
	public static void main(String[] args) {    
	Cat garfield = new Cat("Long-hair", true);  
	}
}
```

A class can contain multiple constructors as long as they have different parameter values. A signature helps the compiler differentiate between the different constructors.

A signature is made up of the constructor’s name and a list of its parameters.