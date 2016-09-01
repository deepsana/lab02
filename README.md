# Lab 02 -- Chapter 01

## Define the following terms:
* object – It holds both variables and methods. It can be represented as either you for someone and me for someone else.
* class – The blueprint from which individual objects are created. 
* instance – same as object. It refers to a specific object of a specific type. 
* method – a collection of statements that are grouped together to perform an operation.
* signature – a part of the method declaration.
* parameter – It is what appears in the definition of the method. It refers to any declaration within the parentheses following the method/function name in a method/function declaration or definition.
* type – When introducing it, give a full list of built-in data types.
* state – It is more of a usage pattern rather than being a way to define a class’s properties.
* source code – instructions that the programmer uses to build the program.
* return value, - It defines and constrains the data type for the returned value from a method.
* compiler –  it translates the code that is written by the programmer into instructions for the computer  to use. 

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)
Data types:
byte – It is an 8-bit signed two’s complement integer and has a minimum value of -128 and maximum value of 127. It is used for saving memory in large arrays where the memory savings actually matters and can be used instead of int where their limits help clarify the written code.
short – It is a 16-bit signed two’s complement integer with a minimum value of -32,768 and maximum of 32,767. It can be used for a short to save memory in large arrays.
int – It is a 32-bit signed two's complement integer with a minimum value of -231 and a maximum value of 231-1. It is used as an unsigned integer.
long – It is a 64-bit two's complement integer. It has a minimum value of 0 and a maximum value of 264-1 in Java SE 8 and later.  It has methods such as compareUnsigned, divideUnsigned etc to support arithmetic operations for unsigned long.
float – It is a single-precision 32-bit IEEE 754 floating point. It is used to save memory in large arrays of floating point numbers.
double – It  is a double-precision 64-bit IEEE 754 floating point. It is used for the decimal values and shouldn’t be used for precise values.
boolean – It has only 2 possible value – true and false.It is used for simple flags that is used to track true and false conditions.
char – It is a single 16-bit Unicode character with minimum value of 0 and maximum value of 65,535 inclusive.

## What are the types of the following values?


* 0 – int
* "hello" - string
* 101 - int
* -1 - int
* true - boolean
* "33" - string
* 3.1415 - float, double


## What would you have to do to add a new field, for example one called name, to a circle object?
By using class object to go through fields,
## Write the header for a method named send that has one parameter of type String, and does not return a value.
public void send(String send)
## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
public int average(int firstInt, int secondInt)
## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.
It is an object of class iBooks.

## Can an object have several different classes? Discuss.
An object cannot have several different classes since it only has a particular class the defines the field and method of objects.
