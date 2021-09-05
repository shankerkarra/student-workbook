# Week 10( Day 1)

## What are the three categories of data types? How are they different?

The three categories of data types are

Value type
Reference type
Pointer type

Value type, a data type, which holds a data value within its own memory. Where as when value is passed to another method, a seperate copy of the value is passed. If the value is changed in one method, it doesn't effect the other copy.


Reference Type, a data type, which stores the pointer address, where the value is being stored. When Referene data type is passed to another method, any changes in the data will be reflected to all the reference pointers.

Pointer type, a data type, which is a referent type and unmanaged types can be referent type.

## What are the Value-type data types? What differences do you notice from JavaScript?

The value-type data types are  bool, byte, char, decimal, double, enum, float, int, long, sbyte,short,struct,uint,ulong,ushort

The difference noticed is in C# it is typed data type, while javascript is dynamically typed.

Boolean is numerically evaluated in Javascript, where as in C# it is only true or false.

Javascript supports only 16-bit unsigned int, where as C# supports unsigned 8-bit, 16-bit,32-bit & 64-bit integers.

Javascript doesn't support complex numbers, where as C# support complex numbers.

Javascript doesn't support primitive value type, where as C# support user-defined value type.

Javascript doesn't support tuples where as C# support tuples.

Javascript doesn't support pointers, where as C# support pointers.

## In your own words how do Reference types get stored in memory? How does this differ from Value types?

Reference Types are stored in the heap, when a reference types is declared, the address location of the actual value is stored and the address location is shared when copied. If the data is changed, the variable reference automatically reflects it.

Where as in value type, direct value can be assgined and the data is stored in Stack, and when passed as a parameter, a copy of the variable is created. Hence if the variable is changed, it doesn't reflect at other copied variable.

Value data types cannot be inherited where as reference type can. 
Value types can be implemented as structure, where as reference types as class.

Lab Url: https://github.com/shankerkarra/csharpday1.git