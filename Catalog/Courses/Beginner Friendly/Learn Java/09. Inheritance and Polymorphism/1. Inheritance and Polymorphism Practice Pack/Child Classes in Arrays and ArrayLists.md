# Child Classes in Arrays and ArrayLists

```java
// Animal parent class with child classes Cat, Dog, and Pig. 
Animal cat1, dog1, pig1;
 
cat1 = new Cat();
dog1 = new Dog();
pig1 = new Pig();
 
// Set up an array with instances of each animal
Animal[] animals = {cat1, dog1, pig1};
 
// Iterate through the list of animals and perform the same action with each
for (Animal animal : animals) {
  
  animal.sound();
  
}
```

In Java, polymorphism allows us to put instances of different classes that share a parent class together in an array or `ArrayList`.

For example, if we have an `Animal` parent class with child classes `Cat`, `Dog`, and `Pig` we can set up an array with instances of each animal and then iterate through the list of animals to perform the same action on each.