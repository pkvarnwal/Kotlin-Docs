# Kotlin Guidelines

### var
### val
### Companion Objects

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

