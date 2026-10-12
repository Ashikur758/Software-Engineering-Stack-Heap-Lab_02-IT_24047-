# Java Lab Practice: Stack and Heap Memory

## Objective
To demonstrate Stack Frames, Heap Objects, Instance Variables, Local Variables, and Object Identity Hash Codes in Java.

## Problem 1: Student Class
- Created a `Student` class.
- Declared `age` as an instance variable.
- Declared `marks` inside the `display()` method.
- Created a Student object in `main()`.
- Displayed its identity hash code.

## Problem 2: Employee and Local Inner Class
- Created an `Employee` class with an instance variable `salary`.
- Displayed the local variable/parameter `bonus`.
- Created a local inner class named `Report`.
- Created Employee and Report objects.
- Displayed both identity hash codes.
- Used the `show()` method to display the employee's salary.

## Memory Concepts
- Employee, Student, and Report objects are generally allocated on the heap.
- Instance variables are part of their respective objects.
- Local variables and method parameters are associated with method execution and are commonly explained using stack frames.
- A method call uses a stack frame.
- `System.identityHashCode()` returns an identity-based hash code, not an actual memory address.

## How to Run

```bash
javac Student.java
java Student

javac Employee.java
java Employee
```

## Conclusion
The programs demonstrate the basic concepts of Java Stack Frames, Heap Objects, Instance Variables, Local Variables, and Local Inner Classes.
