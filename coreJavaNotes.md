---
title: Core Java Learning Notes
summary: This are note copied from learning Core Java from other sources
authors:
    - Tamba Fayiah
date: 2025-05-31
---
# Data Types
- Java is a statically-typed _meaning all variables must first be declared with their appropiate datatypes stated before use_.
- Data types in java specify the kind/type of information a variable/computer will not in momery at a given space or time. 
- variable declaration and initialization require statin the: <data type>  <variable name > < equal (assignment) sign> and <value>
--------
{
    int gear =1; //declare an  integer variable and initialized it with one
}
----------

## The kinds of data types
In Java, there a two main kind of data types, they are primitive data types and non-primitive data types.

    ### 1. Primitive datatype:
    - they are the fundamental java data types. They can store either; numbers (whole or decimal), char or boolean (true/false).  
    -  java supports seven (7)  primitive data types. 
      
       ####  a.  byte:  
        - An 8-bitt signed (take both negative and positive values) integer. 
        - Its minimum value is -128 and max value is 127
        - useful for saving memory in large arrays, also used inplace of int where their limits help to clarify code. 
        
        #### b. short: 
        - A 16-bit signed integer. 
        - Its minimum value is -32,768 and max value is 32767
        - useful for saving memory in large arrays. 
        
        #### c: int:
        - 32-bit signed integer by default. 
        - minimum value -2^31 an max value 2^31-1
        - However, since java SE 8, int can be used to represent a 32-bit unsigned integer ranging from 0 to 2^32-1
        - The class Integer in the java lang library have static methods such as compareUnsigned, divideUnsigned that support arihmetic operations for unsigned integers
        
        #### d. long:
        - 64-bit signed integer, with higher range than int and previous mentioned integers primitive types. 
        - Its minimum value is -2^63 , and maximum value 2^63-1.
        - In Java SE 8 and later, you can use the long data type to represent an unsigned 64-bit long, which has a minimum value of 0 and a maximum value of 264-1.
        - The class Long contains mothods like compareUnsigned, divideUnsigned etc to support arithmetic operations for unsigned long. 
        
        #### e. float:
        
        
        
        
        
        
    For more details on java primitive datatypes, Visit the officical oracle tutorial page at [Java primitive datatypes - tutorial](.https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html) .
