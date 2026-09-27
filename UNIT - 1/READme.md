 1. Class and Object Program

This program explains the fundamental concept of **classes and objects in C++**. A class named `Student` is defined with two data members, `name` and `age`, along with a member function `show()` to display the student's information. An object `s1` is created from the `Student` class, values are assigned to it, and the `show()` function is used to display the details.

### 2. Constructor and Destructor Program

This program demonstrates the working of **constructors and destructors in C++**. The `Demo()` constructor is called automatically when the object `d` is created. Similarly, the `~Demo()` destructor is automatically invoked when the object goes out of scope at the end of the `main()` function. Both functions display messages to indicate when they are executed.

### 3. Inline Member Function and Friend Function

This program demonstrates the use of **inline member functions and friend functions** for accessing private class data. The `Test` class contains a private integer value that can be accessed using the `getValue()` inline member function, which is defined inside the class for efficient execution. The program also declares an external function `show()` as a friend function, allowing it to access and display the private data of a `Test` object directly.

### 4. Static Member

This program demonstrates the concept of a **static data member** that is shared among all objects of a class. A static integer variable named `count` is declared inside the `Student` class and initialized to zero outside the class. Since a static variable belongs to the class rather than a particular object, all objects share the same `count` variable. Whenever a new `Student` object is created, the constructor increases the value of `count`, making it possible to keep track of the total number of objects created.
