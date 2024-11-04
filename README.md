Java Object-Oriented Programming Examples
This repository contains three Java programs demonstrating the concepts of inheritance, polymorphism, abstract classes, and interfaces in Java. Each program is structured to highlight a different aspect of object-oriented programming.

Table of Contents
Vehicle and Derived Classes
Shape and Area Calculation
Abstract Classes and Interfaces with Animals and Pets
How to Run
1. Vehicle and Derived Classes
This program demonstrates inheritance, method overriding, and polymorphism using a base class Vehicle and derived classes Car and Bike. Each derived class overrides methods to provide specific implementations for start and description.

Files:
Vehicle.java
Key Concepts:
Inheritance
Method Overriding
Polymorphism
Example Output:
plaintext
Copy code
Sedan (Car) is starting with a roar.
Sedan (Car) with 4 doors can go up to 200 km/h.
Sports Bike (Bike) is starting with a vroom.
Sports Bike (Bike), which is a sport, can go up to 150 km/h.
2. Shape and Area Calculation
This program demonstrates the use of abstract classes by creating a base class Shape with derived classes Circle, Rectangle, and Triangle. Each derived class implements an overridden method to calculate its area.

Files:
Shape.java
Key Concepts:
Abstract Classes
Polymorphism
Method Overriding
Example Output:
plaintext
Copy code
Area: 78.53981633974483     // Circle with radius 5
Area: 24.0                  // Rectangle with length 4 and width 6
Area: 12.0                  // Triangle with base 3 and height 8
3. Abstract Classes and Interfaces with Animals and Pets
This program demonstrates the use of abstract classes and interfaces. We define an abstract class Animal and an interface Pet. The derived classes Dog and Cat implement the Pet interface and override the abstract methods in Animal.

Files:
Animal.java
Key Concepts:
Abstract Classes
Interfaces
Multiple Inheritance through Interfaces
Polymorphism
Example Output:
plaintext
Copy code
Buddy says: Woof Woof!
Buddy loves to play fetch!
Buddy is sleeping.

Whiskers says: Meow Meow!
Whiskers loves to play with a ball of yarn!
Whiskers is sleeping.
How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/Java-OOP-Examples.git
cd Java-OOP-Examples
Compile the Java files. For example:

bash
Copy code
javac Vehicle.java
javac Shape.java
javac Animal.java
Run the compiled files:

bash
Copy code
java Vehicle   // To run the Vehicle and Derived Classes example
java Shape     // To run the Shape and Area Calculation example
java Animal    // To run the Abstract Classes and Interfaces example
License
This project is licensed under the MIT License.
