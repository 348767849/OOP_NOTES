#Encapsulation

Information hiding: Restricting the access to the classes/objects as well as certain attributes and methods.
we do this to protect data and prevent certain methods from being callable

we use __ as a prefix(in front) to his attributes and methods

#Overides and Ovrloading(with a bit of inheritance)

Overloading: Two same  methods in one class but have different parameters 
Overriding: Two exact same methods in a class. The Parent and child where the child will be tailored to be more specific.

#polymorphism
A method that can be used across different classes and object that is dependent on the parameters. 
(A lion may sound different than a dog)

#Base Overrides(aka magic methods)

Two different classes have a same attributes and methods 


A child of a parent have an overrided method where the child would utilize the method differently.
These are the two fundamental concepts of overriding and polymorphism in Python.
If we we can override a built-in methods/operators that we use in Python 3 as well for our own objects.
Some website calls them “magic methods”

#__repr__() base functions
when we need to make object printable we do one of these:
_repr__ → Allows us to present a printable version of our object
__str__ → Allows us to convert our object to a string



