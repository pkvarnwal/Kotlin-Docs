# Kotlin Guidelines

### var
### val
### Companion Objects
### Functional and object-oriented
### Object-Oriented Programming in Kotlin

### var:
* `var` is like general variable and its known as a mutuable variable in `Kotlin` and can be assigned multiple times.

### val:
* `val` is like constant variable and its known as immutable in kotlin and can be initialized only single time.

### Companion Objects:
* In Kotlin, unlike Java or C#, classes do not have static methods. In most cases, it's recommended to simply 
  use package-level functions instead.
  If you need to write a function that can be called without having a class instance but needs access to the internals of a class 
  (for example, a factory method) you can write it as a member of an `object declaration` inside that class.
  Even more specifically, If you declare a `companion object` inside your class, you'll be able to call its members with 
  the same syntax as calling static methods in java/C#, using only the class name as a qualifier.

### Functional and object-oriented:

*As a Java developer, you’re no doubt familiar with the core concepts of object-oriented
programming, but functional programming may be new to you. The key concepts of
functional programming are as follows:* 

* *First-class functions*: You work with functions(pieces of behavior) as values. You can store them in variables, 
  pass them as parameters, or return them from other functions.
* *Immutability*: You work with immutable objects, which guarantees that their state can't change after their creation.
* *No side effects*: You use pure functions that return the same result given in same inputs and don't modify the state
  of other objects or interact with the outside world.

### Object-Oriented Programming in Kotlin

* Kotlin is an object-oriented programming (OOP) language with support for higher-order functions and lambdas.
If you don't know what lambdas are, don't worry, there is a full chapter dedicated to them. 
If you have been using a functional language already, you will find functional language-like constructs supported in Kotlin.
Over time, software complexity has increased, and the OOP abstraction has allowed us 
to model the problem we have to solve in terms of objects.
You can view each object as a minicomputer on its own: it has a state and can perform actions.
An object through its available actions exhibits some sort of behavior; 
therefore, there is a clear analogy between objects/entities and real life.
