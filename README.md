# Lab 02 -- Chapter 01

## Define the following terms:
* object : State or behavior (instance) of a class.
* class: blueprint (guidelines) that defines how to create an object.
* instance: Specific realization of any object.
* method: A collection of statements, in a class, used to manipulate (mutators) or access (accessors) information from an object of that class (behaves like a function in mathematics).
* signature(or heading): Name of the method and type of parameter. I.e. the following signature changes the size of the instance `box` of class `Box` and does not give an output.
```
void changeSize(Box box)
```
* parameter: An input of the method. I.e. `box` is the parameter in the example above.
* type: Defines what values the parameter is allowed to be.
* state: Set of values describing an object.
* source code: Collection of written commands that compiles to create an executable program.
* return value: Output of a method.
* compiler: Transforms source code into computer readable language (forces computer to read the instructions).
 

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)
Data types:
byte – It is an 8-bit signed two’s complement integer and has a minimum value of -128 and maximum value of 127. It is used for saving memory in large arrays where the memory savings actually matters and can be used instead of int where their limits help clarify the written code. 
short – It is a 16-bit signed two’s complement integer with a minimum value of -32,768 and maximum of 32,767. It can be used for a short to save memory in large arrays. 
int – It is a 32-bit signed two's complement integer with a minimum value of -231 and a maximum value of 231-1. It is used as an unsigned integer. 
long – It is a 64-bit two's complement integer. It has a minimum value of 0 and a maximum value of 264-1 in Java SE 8 and later. It has methods such as compareUnsigned, divideUnsigned etc to support arithmetic operations for unsigned long. 
float – It is a single-precision 32-bit IEEE 754 floating point. It is used to save memory in large arrays of floating point numbers. 
double – It is a double-precision 64-bit IEEE 754 floating point. It is used for the decimal values and shouldn’t be used for precise values. 
boolean – It has only 2 possible value – true and false.It is used for simple flags that is used to track true and false conditions. 
char – It is a single 16-bit Unicode character with minimum value of 0 and maximum value of 65,535 inclusive.

## What are the types of the following values?

* 0 ::int, double, float?
* "hello" :: String
* 101 :: int, double, float?
* -1 :: int, double, float?
* true ::boolean
* "33" :: String
* 3.1415 :: float?, double


## What would you have to do to add a new field, for example one called name, to a circle object?
```
private String name;
```
## Write the header for a method named send that has one parameter of type String, and does not return a value.
```
public void send(String var1)
```
## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
```
public int average(int firstInt, int secondInt)
```
## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.
The book is an object of class Books.
Or the book is a class called BlueJBook and the objects are different copies of the book.

## Can an object have several different classes? Discuss.
Up for discussion.
An object cannot have several different classes since it only has a particular class the defines the field and method of objects.
