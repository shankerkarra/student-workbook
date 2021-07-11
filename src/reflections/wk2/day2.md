## What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

Functional declaration, has the syntax of Function followed by name and a list of parameters in pair of parenthesis; and a pair od bracs where the code body is written.

Anonymous function are functions without a name. Callback functions are treated as anonymous.

Favor named function is where the function is assigned to a variable.

An arrow functions are functions defined using a pair of parenthesis, with a list of parameters, followed by =>(lambda functions) and with a pair of curly braces.

## What is the difference between Parameters and Arguments?

Parameters are the aliases for the values being passed to the function and arguments are the actual values.

## What are higher order functions? Can you provide an example?

A high order functions that takes another function as a parameter.

Ex; 
function hello(callfunction){callfunction();}
function print() { console.log('Hello');
hello(print);