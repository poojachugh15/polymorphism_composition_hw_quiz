# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
   'polymorphism' means the ability to take many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
   It allows us to perform a single action in different ways. For example, a class Dog may extend an abstract class Animal.
   An instance of the Dog class is also an instance of the Animal class so could be used wherever an Animal type is required in the function.

3. What can we use to implement polymorphism in Java?
   We can use interfaces and inheritance.

4. How many 'forms' can an object take when using polymorphism?
   I think it depends on how many interfaces it has.

5. Give an example of when you could use polymorphism.
   We have one parent class, an Account with the function of deposit and withdraw and Account has two child classes.
   The operation of deposit and withdraw is the same for Saving and Checking Accounts.
   So the inherited methods from the Account class will work.


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
   A composition is a specialized form of aggregation. In composition, if the parent object is destroyed,
   then the child objects also cease to exist.

7. When would you use composition? Provide a simple example in Java.
   We use composition because it allows us to reuse code without modeling an is-a association as we do by using inheritance. For example, Car and a Vehicle share the ‘IS-A’ relationship as a car is a vehicle. Hence we create a car object from the existing vehicle object by adding more characteristics to it.
   Car and Engine share the ‘Has-a’ relationship. A car always has an Engine.
   So what we do here is that we do not extend the properties of the Engine object but we use the Engine object directly.
   This is done in Java using composition.

8. Give a difference between composition and aggregation?
   The composition is a strong type of association. An association is said to composition if an Object owns another object and another object cannot exist without the owner object. Consider the case of a Human having a heart.
   Here Human object contains the heart and the heart cannot exist without humans.
   Aggregation is a weak association. An association is said to be aggregation if both Objects can exist independently. For example, a Team object and a Player object.
   The team contains multiple players but a player can exist without a team.

9. What is/are the advantage(s) of using composition/aggregation?
   Composition is more flexible. You can change the implementation of class at run-time by changing the included object,
   thus changing the behavior of it,

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
    When the owning object is destroyed, so are the contained objects.
11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
    They don't need to destroy and they can exist.