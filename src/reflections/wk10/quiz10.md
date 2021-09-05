# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
namespace is a logical grouping of classes and to discourage name collusions.

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Class is a reference Data types, whereas struc is value data type.
Class object is stored in heap and struct variable is stored in stack or inline type.
Class can be instantiated with new keyword, where as struct can be instantiated both with & without new.
Class has parameter constructor(if user doesn't defined ), where as struct doesn't contain any constructor.
Class has a destructor/garbage collection, where as struct doesn't have any destructor/garbage collection.
Class can be inherited from another class, where as struct doesn't allow inheritance.
Class members can be abstract, virtual and protected, whereas struct members doesn't allow.
Class instance is called as object, where as struct instance is called structured variable.
Class can be used for complex data structure, where as struct is only for small data structures.

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Abstract and  Main.

Main method return is void. 

Abstract method after implementation, can return an instance of a class, but it doesn't have return type.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
data type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Use of the abstract prevent instantiation on its own.

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual keyword is used to modify a method in the implementation using override method.

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```

public
private
protected
internal
protected internal
private protected

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
private: the private modifier is used to specify that access is limited to the containing type, so the defined type or member can only be accessed by the code in the same class or structure.

```