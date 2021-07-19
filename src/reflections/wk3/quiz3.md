# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
The pillars of OOP are  Abstraction /  Encapsulation / Inheritance / Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[property];
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is one of the fundamental concept in OOP. It describes the idea of bundling data and methods that work on that data.( ex. Class).

```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
In SOLID principles, S stands for Single Responsibility Principle.

SOLID is an acronym where
S stands for SRP (Single Responsibility Principle)
O stands for OCP (Open Closed Principle)
L stands for LSP (Liskov Substitution Principle)
I stand for ISP (Interface Segregation Principle)
D stands for DIP (Dependency Inversion Principle).

```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
Class is a blue print and instance of a class a copy of the blueprint.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Proxy objects are transparent to the client and acts like aintermediatary between the client and  acessible objects.

```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
MVC pattern allows the seperation of business logic with presentation. The controller provides the support for data massaging, prior to forwarding it to mode & view. The Model and view are interconnected and execution is reflected by view.

```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is to interpret the incoming data, modify, and provide data for the view and communicate with view and service / Model layer.

```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Service provides high-level logic for the application. Service layer can ve invoked by the controller and view helpers.
```

**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Model is the architecture of representing the data andhow it is structured. Model communicated when a change in data, notifies view to refresh the dom.

```

