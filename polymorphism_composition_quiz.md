# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

In this context it is the ability of one thing to be represented by many.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

We could use interfaces to implement shared behaviours to different objects. In the implementation we also give the object the ability to be represented by the interface.
```
private class Guitar implements IMakeSound{}
```
3. What can we use to implement polymorphism in Java?

Interfaces and parent or super classes.

4. How many 'forms' can an object take when using polymorphism?

It can only take one form at a time, but using multiple interfaces it could take as many as given.

5. Give an example of when you could use polymorphism.

If something has a shared/similar behaviour that another class can implement. e.g in the example of the computer components they were all able to output something, but they were able to be polymorphed to output something specific to itself.


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

When an object has (an)other object(s) under its ownership.


7. When would you use composition? Provide a simple example in Java.

Using the lab's example, a car has ownership over the engine, and a car is 'composed' of an engine (and other parts).
```
private Class Guitar implements IMakeSound{
    Pickup pickup;
}
```

8. What is/are the advantage(s) of using composition?

The higher class can use the component class with all of it's behaviours/properties without necessarily having to worry about inheritance chains or interfaces.

9. When an object is destroyed, what happens to all the objects it is composed of?

Destroyed in the context of that object.