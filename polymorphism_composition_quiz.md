# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

    The concept of having multiple forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

It means that we can have a class be of many types, which saves from methods needing to be overloaded and other issues. In Java this works as a class being able to have a parent class in an inheritance chain (and have the class of its parent etc.) or to have the same type as any number of interfaces it implements such as in the below example

```java
public class ElectricCar extends Car implements IDrive, IRefuel {

} 


```



3. What can we use to implement polymorphism in Java?

Interfaces and Inheritance

4. How many 'forms' can an object take when using polymorphism?

It can inherit from one thing, and implement many things. The thing it inherits from can also inherit from something else in a chain up to Object.

5. Give an example of when you could use polymorphism.

If we wanted an owner to be able to have multiple types of car, and mutltiple objects that drove, in the above example


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

Creating one class from component classes.

7. When would you use composition? Provide a simple example in Java.

If we wanted a class to be able to do things that other sub classes can do without creating an inheritance chain

8. What is/are the advantage(s) of using composition?

You don't have to create big messy inheritance chains

9. When an object is destroyed, what happens to all the objects it is composed of?

It is also destroyed