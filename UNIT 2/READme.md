Name-Vikalp Jangale
Class-SY-B
Roll no-AD2223
ZPRN-125UAD1198 
1. Abstract Class
This program explains the concept of an abstract class and pure virtual functions in C++. An abstract class named Shape contains a pure virtual function area(), so objects of the Shape class cannot be created directly. The Rectangle and Circle classes inherit from Shape and implement their own versions of the area() function. The program creates objects of these derived classes and calculates their respective areas.

2. Basic Single Inheritance
This program demonstrates single inheritance, in which one derived class inherits the features of a single base class. The Person class stores a person's name and provides a function to display it. The Student class inherits from Person and adds a roll number. It uses the inherited function along with its own functionality to display the complete student information.

3. Constructor and Destructor Order
This program demonstrates the order in which constructors and destructors are called during inheritance. A Base class and a Derived class are created, with each class having its own constructor and destructor. When an object of the derived class is created, the base constructor executes first, followed by the derived constructor. During object destruction, the order is reversed: the derived destructor runs first and then the base destructor.

4. Employee Payroll System
This program creates an employee payroll system using abstraction and polymorphism. The abstract Employee class contains common employee information such as ID and name and declares a pure virtual calculateSalary() function. PermanentEmployee and ContractEmployee provide their own salary calculation methods. A displayPaySlip function uses a base-class reference to calculate and display the appropriate salary based on the employee type.

5. Friend Class
This program demonstrates how a friend class can access private members of another class. The Account class contains a private balance variable and declares the Auditor class as its friend. Because of this friendship, the Auditor class can directly access and display the private balance of an Account object.

6. Function Overriding
This program explains function overriding, which is an important part of runtime polymorphism. The base Vehicle class contains a virtual move() function. The derived Car and Boat classes redefine this function to provide their own movement descriptions. When the function is called for each object, the appropriate overridden version is executed.

7. Hierarchical Inheritance
This program demonstrates hierarchical inheritance, where multiple derived classes inherit from the same base class. The Car and Bike classes both inherit common features such as the registration number and start() function from the Vehicle class. Each derived class also contains its own specialized function, such as openBoot() for the car and helmetReminder() for the bike.

8. Multilevel Inheritance
This program illustrates multilevel inheritance, where inheritance takes place through multiple levels. The Person class is the base class, Employee inherits from Person, and Manager further inherits from Employee. As a result, a Manager object can access the properties inherited from both Person and Employee, along with its own team size information.

9. Multiple Inheritance
This program demonstrates multiple inheritance, where one class inherits from two or more base classes. The Student class inherits from both Academic and Sports. The two base classes provide academic and sports marks respectively. The Student class can access these inherited values and calculate the overall total.

10. Multiple Inheritance Ambiguity
This program explains the ambiguity that can occur in multiple inheritance. Both the Academic and Sports classes contain a function named display(). When the Student class inherits from both classes, the compiler cannot automatically determine which display() function should be called. The scope resolution operator (::) is therefore used to specifically call either Academic::display() or Sports::display().

11. Nested Class
This program demonstrates a nested class, where a class is declared inside another class. The University class contains an inner Department class. The nested class has its own data and display function. In the main() function, the inner class is accessed using University::Department, showing how related classes can be grouped together.

12. Parameterized Base Constructor
This program demonstrates how a derived class can initialize a base class using a parameterized constructor. The Person class has a constructor that accepts a name as an argument. When a Student object is created, its constructor uses an initialization list to call the Person constructor and pass the required name. The student-specific roll number is then initialized separately.

13. Protected Member Access
This program explains the use of the protected access specifier in inheritance. The Employee class contains a protected name variable. Although the variable cannot be accessed directly from outside the class, it can be accessed by derived classes. The Developer class uses this inherited variable along with its own programming language information to display the details.

14. Public and Private Inheritance
This program demonstrates the difference between public and private inheritance. In PublicDerived, the base class's public show() function remains accessible as a public member. In PrivateDerived, the inherited show() function becomes private. Therefore, a public wrapper function named callBaseShow() is provided to access the base function from outside the class.

15. Vehicle Rental System
This program implements a simple vehicle rental system using inheritance, virtual functions, and overriding. The base Vehicle class provides functions for displaying vehicle information and calculating daily rent. The Car class adds the number of doors, while the Bike class adds engine capacity and provides its own rent calculation with a 10% discount. This demonstrates how derived classes can modify inherited functionality.

16. Virtual Base Class
This program demonstrates the use of a virtual base class to solve the diamond problem in multiple inheritance. Both Student and Employee virtually inherit from the Person class. When TeachingAssistant inherits from both Student and Employee, virtual inheritance ensures that only one shared Person object exists. This avoids duplicate data and removes ambiguity while allowing the common base class to be initialized properly.
