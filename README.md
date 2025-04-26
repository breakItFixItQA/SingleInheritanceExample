# SingleInheritanceExample
Single Inheritance Example in Java
📋 Overview
This project demonstrates Single Inheritance in Java, where one class (Child) inherits directly from a parent class (Parent).

It shows:

How a child class can inherit fields and methods from its parent class.

How a child class can also define its own unique fields and methods.

📂 Project Structure
Parent class:

Property: familyName (String)

Method: greet() (Prints a greeting message from the parent)

Child class (extends Parent):

Property: age (int)

Method: welcome() (Prints a welcome message from the child)

SingleInheritanceExample class:

Contains the main() method.

Creates an instance of Child.

Demonstrates accessing both inherited and child-specific properties and methods.

🚀 How It Works
The Child object:

Accesses its own property (age) and method (welcome()).

Inherits and accesses the parent's property (familyName) and method (greet()).

🛠 Example Output
vbnet
Copy
Edit
Child's age: 10
Family Name: Smith
Welcome from Child
Hello from Parent!
📚 Concepts Demonstrated
Inheritance (Single Inheritance)

Method and Property Inheritance

Fundamental Object-Oriented Programming (OOP) Concepts

