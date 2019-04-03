# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

*The word polymorphism means 'many forms'.*

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

*In Java it means that a single object can be of many different types*

*For example, we could have objects of type building and car - both of which could have a holds people function*

3. What can we use to implement polymorphism in Java?

*We can use interfaces to implement polymorphism in Java*


4. How many 'forms' can an object take when using polymorphism?
*An object can take an infinite number of forms using Polymorphism. So long as it implements the specific methods defined in the interfaces*

5. Give an example of when you could use polymorphism.
*Suppose I had a building class and a vehicle class as above, and in a separate class I had an entire penal system which had an collection of all the jails, detention centres and buses to and fro (roll with it) from that class I wanted to count all the people in the system - I wanted a count people function which would iterate over said array. In a statically typed language, I'd need to type the ArrayList either vehicles or buildings. Using polymorphism  via an ICounter interface I can type the ArrayList  which would link the countPerson function of both*



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
*composition means an object contains other objects - their relationship described as a 'has a' relationship.*

7. When would you use composition? Provide a simple example in Java.
*Suppose we had a body class which contained objects of muscle type, organ type, limb type etc which all have one linked function they getWeight() composition can be used to assign those component parts to the body class whose type (as with limb) may only be related to high level function.s*

8. What is/are the advantage(s) of using composition?
*Composition allows objects which would not normally be related (via inheritance) to be linked via interfaces*
*Composition allows you to implement one method with many different 'strategies' i.e. ways of achieving the same method*
*Composition allows you call methods with the same name across many different types of object*

9. When an object is destroyed, what happens to all the objects it is composed of?
*They are destroyed also*
