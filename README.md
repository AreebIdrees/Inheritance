# Inheritance
Class Inheritance
Defining Base and Derived Classes
In C++, you can define a base class and then create derived classes that inherit properties 

Access Control
C++ supports access control for base class members in derived classes. You can use public, protected, or private access specifiers when inheriting:

Constructor and Destructor Inheritance
Constructors and destructors are inherited but not automatically called by derived classes. You can explicitly call the base class constructor and destructor from the derived class:



Algorithm
Start
Define a base class named Vehicle with the following properties:
A string brand initialized to "Ford_"
A member function color() that prints "Red!" to the console.
Define a derived class named Car that inherits from the Vehicle base class.
In the main function, create an object myCar of the Car class.
Call the color() function on myCar to print "Red!" to the console.
Display the combination of myCar's brand and model.
End


Single Inheritance (Part 2)
Algorithm
Start
Define a base class named name with a constructor that prints "This is Pranav" to the console.
Define a derived class named Firstname that inherits from the name base class.
In the main function, create an object obj of the Firstname class.
The constructor of the name base class is called, printing "This is Pranav" to the console.
End
