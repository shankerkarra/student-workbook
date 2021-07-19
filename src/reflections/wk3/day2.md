# Week 3( Day 2)

## JS > Encapsulation in JavaScript and answer the following questions

## What is the purpose of Encapsulation?

Encapsulation is bundling data and the methods, that act on the data. Data accessing from outside is restricted.


## What were some of the problems with closures and the underscore prefix?

Underscore prefix a common notation to imply that the variable is private. Even if it is treated as private, but can still be accessed and mutated using object._variable name.

where as closure, when a function is finished executing the declared variables are garbage collected.

entry level developer miss the notation of underscore and can lead to application crashing.

## How do we create private variables in a ES6 Class? Why would you do this?

ES6 clases doesn't allow variable declaration outside the construtor, making it harder to work with class in OOP way. And variable declared in the constructor are by default public.

Private variables are created inside the class with # prefix variable inside the class body and can be accessed inside by class members functions.

Lab Url: https://github.com/shankerkarra/vendingmachine.git