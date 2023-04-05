#inheritance

Inheritance: When an object or class is based on another class; where its features are from a parent class
Types:
Single Inheritance: A subclass inheriting the features of a single superclass / parent class
Multiple Inheritance: A subclass inheriting the features of a multiple parent classes
Multilevel Inheritance: A subclass is inheriting from another subclass… A → B → C
Inheritance can have an hierarchy (branching like a tree) and/or be a hybrid: mixing the types of inheritances

If a child class inherits the parent class:
The child does not need a new __init__() method UNLESS it requires new attributes
The child does not need to reinstate the parent’s methods UNLESS you override them

super() → is a built-in method for classes to refer their parent class
This prevents us from doing ParentClass.method(self)
The self with self gets confusing… 

#Dont Use inheritance unless you know you gotta

