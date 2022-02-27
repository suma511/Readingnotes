# Maps, primitives, File I/O

## primative & Refrance
java have tow type system the primative one : such us int and boolean and Refrance : such as Integer Boolean 
Every premative type refers to the refranse one 
Every object contains value of the primitive type their state can't change once the object is constructed

we deal with tow process to convert from one type to another 
autoboxing:The process of converting a primitive type to a reference one//Integer j = 1;  
unboxing:The process of converting a refrance type to a primitive one//int i = new Integer(1); 
 
 We have sth called Pros and Cons
 it is the decision what object is to be used is based on what application performance we try to achieve, how much available memory we have, the amount of available memory and what default values we should handle.
 Each one of this tow types have a certain space took from memory  
 there is different in performance and in speed between primative and refrance also there is a diffrent inside the type itself
 as what is written the double has the higher excution time and the bool  is the lowest
 As we've seen, the primitive types are much faster and require much less memory. Therefore, we might want to prefer using them.

## Exceptions
An exception is an event that occurs during the execution of a program that disrupts the normal flow of instructions.

When an error occurs within a method, the method creates an object and hands it off to the runtime system. The object, called an exception object, contains information about the error, including its type and the state of the program when the error occurred. Creating an exception object and handing it to the runtime system is called throwing an exception.
Types of excotions
- checked exception
- error
- runtime exception
there is a way to throgh the exceptions 
you can create your own set of exception as a developer to allow users to differentiate an error that can occur in your package from errors that occur in the Java platform or other packages .

there is three ways to catch the errors 
The try block identifies a block of code in which an exception can occur.
The catch block identifies a block of code, known as an exception handler, that can handle a particular type of exception.
The finally block identifies a block of code that is guaranteed to execute, and is the right place to close files, recover resources, and otherwise clean up after the code enclosed in the try block.

## Scanning
Objects of type Scanner are useful for breaking down formatted input into tokens and translating individual tokens according to their data type. scanner uses white space to separate tokens