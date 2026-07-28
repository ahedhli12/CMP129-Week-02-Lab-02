CMP 129 – Computer Science II
Week 2 – Lab 2: Classes, Objects, and Constructors
Learning Objectives

After completing this lab, students should be able to:

Define a Java class with private attributes.
Create objects from a class.
Apply data encapsulation using getter and setter methods.
Create and use a parameterized constructor.
Call instance methods using objects.
Test a class using a separate test class.

Complete both assignments. Each assignment must be placed in its own folder.

Assignment 1: Person Class Without a Defined Constructor

Create a Java class named Person that stores information about a person. Do not define a constructor in this version. Java will provide the default no-argument constructor automatically.

Person Class Requirements

Create a file named:

Person.java

The Person class must contain the following private attributes:

name — a String
age — an int
email — a String

Implement getter and setter methods for every attribute:

getName()
setName()
getAge()
setAge()
getEmail()
setEmail()

Create a method named:

displayInfo()

The method must display the person’s name, age, and email in a clear, formatted manner.

PersonTest Class Requirements

Create a separate file named:

PersonTest.java

In the main method:

Create at least two Person objects using the default constructor.
Use the setter methods to assign the name, age, and email of each person.
Use the getter methods to retrieve at least one attribute.
Call displayInfo() for each object.
Example Output Format
Person Information
------------------
Name:  Maria Johnson
Age:   28
Email: maria@example.com

Person Information
------------------
Name:  David Smith
Age:   35
Email: david@example.com

Do not use a parameterized constructor in Assignment 1.

Assignment 2: Person Class With a Constructor

Create another version of the Person class. This version must include a parameterized constructor.

Person Class Requirements

Create a file named:

Person.java

The Person class must contain the following private attributes:

name — a String
age — an int
email — a String

Create a constructor that accepts values for all three attributes:

public Person(String name, int age, String email)

The constructor must initialize the object’s attributes using the values received through its parameters.

Implement getter and setter methods for every attribute:

getName()
setName()
getAge()
setAge()
getEmail()
setEmail()

Create a method named:

displayInfo()

The method must display the person’s name, age, and email in a clear, formatted manner.

PersonTest Class Requirements

Create a separate file named:

PersonTest.java

In the main method:

Create at least two Person objects using the parameterized constructor.
Pass a name, age, and email to the constructor for each object.
Use at least one setter method to update an attribute after an object has been created.
Use at least one getter method to retrieve an attribute.
Call displayInfo() for each object.

Do not use the default no-argument constructor in Assignment 2.

General Requirements
Keep all attributes private.
Follow standard Java naming conventions.
Use the this keyword where appropriate.
Use meaningful variable and object names.
Indent and format the code correctly.
Include comments explaining the class, attributes, constructor, and important methods.
Do not place the main method inside the Person class.
Each PersonTest class must contain a valid main method.
Both assignments must compile and run without errors.
Test every getter, setter, constructor, and displayInfo() method.
You must be able to explain every part of your submitted code.
Follow the course AI-use policy.
Record any AI assistance in AI-Use-Report.md.
Required Organization

Because both assignments use the same class and filenames, organize them in separate folders:

Lab-02
├── Assignment-01-Without-Constructor
│   └── src
│       ├── Person.java
│       └── PersonTest.java
├── Assignment-02-With-Constructor
│   └── src
│       ├── Person.java
│       └── PersonTest.java
├── AI-Use-Report.md
└── CMP129-Week-02-Lab-02.docx
Submission

Push the following files to the Week 2 GitHub repository:

Lab-02/Assignment-01-Without-Constructor/src/Person.java
Lab-02/Assignment-01-Without-Constructor/src/PersonTest.java
Lab-02/Assignment-02-With-Constructor/src/Person.java
Lab-02/Assignment-02-With-Constructor/src/PersonTest.java
Lab-02/AI-Use-Report.md

Make at least two meaningful commits while completing the lab. Use clear commit messages, such as:

Complete Person class without constructor
Add constructor version and test class
