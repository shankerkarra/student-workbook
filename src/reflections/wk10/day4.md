# Week 10( Day 4)

## What is an Enum, and what are some use cases for them?

Enums in C# are strongly typed constants, a unique type that allows to assign symbolic names to integral value.  

Enum is a user-defined data type, used mainly to assign symbolic names to integral values. The names makes readability in the programs and easy to maintain.
For ex: Weekdays (Sun,Mon,Tue,Wed,Thu,Fri,Sat) doesn't  changes, so in application, we can use Enum by specifying an integral values starting from sun or mon; according to the business requirements.

## How can you modify an Enum?

The default values of enum starts with zero and increment to the next values and this process goes on till the end of the enum's. 
In case if we want to modify the starting number, we can directly assign a value, the next number is assigned to the next constant  till end of the enum's. If any of the initial constants are not ssigned a value and if intermediate constants are assigned a value, the initial constants are auto assigned with zero followed by next number till constants have a value.

## How have you used Enums in your afternoon lab projects this far?(if you have not yet, give an example of how you could)

NEED TO WRITE 