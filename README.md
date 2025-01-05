# Lab_9_z_1
This project demonstrates a simple Java program that introduces 
exception handling, specifically focusing on the 
NullPointerException. It's  designed to complete remote descent 
tasks and help understand how to handle runtime exceptions.

The NullException class contains:

A static method generateException() that simulates a scenario 
where a null value is intentionally returned.


The ThrowException class serves as the entry point (main method) of the program.

Calls the generateException() method from the NullException class.
Tries to call .toString() on the returned value, which causes a 
NullPointerException.
Uses a try-catch block to catch the exception and print helpful 
debug information.
