# Protected and Final keywords in Java

```java
class Student {
  protected double gpa;
  // any child class of Student can access gpa 
  
  final protected boolean isStudent() {
    return true;
  }
  // any child class of Student cannot modify isStudent()
}
```

When creating classes in Java, sometimes we may want to control child class access to parent class members. We can use the `protected` and `final` keywords to do just that.

`protected` keeps a parent class member accessible to its child classes, to files within its own package, and by subclasses of this class in another package.

Adding `final` before a parent class method’s access modifier makes it so that any child classes cannot modify that method - it is immutable.