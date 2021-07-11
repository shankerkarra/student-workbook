# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is designed to performa a particular task by the set of code block written  using syntax "function functionname( parameter). The funtion is invoked, either by call from another function or button click.

```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
SOLID stands for Single responsive, open close, listov substitution, Interface segreation & dependency inversion Principle.

```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pineapple - Index is 2

```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push(...them);

```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
Examples of Conditional 

if (20 > 15) {
      var outcome = "Inside the block";
}
​outcome;
OUTPUT
"Inside the block" 

if ("cat" === "dog") {
      var outcome = "if block";
} else {
      var outcome = "else block";
}
outcome;
OUTPUT
"else block"

if (false) {
      var outcome = "if block";
} else if (true) {
      var outcome = "else if block";
} else {
      var outcome = "else block";
}

outcome;
OUTPUT
"else if block"

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM - stands for Document Object Model. The DOM is a programing interface for HTML & XML documents, which represents the documents as nodes and objects.

The first file accessed to render the DOM is HTML. The default page is INdex.HTML, the website can be configured to access another page as default.

```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
The ECMAScript types are 
undefined / Boolean / Number / String / BitINt / Symbol / Object / Function / null.

```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->

```
Parameters are value represents, which function or methods expects to be passed, when it is called.

where as an argument represents the value that is being passed to a procedure,when it is being called.

```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive value are passed(copy) by value; whrere the value are passed as a copy and any changes doesn't effect the original value.

where as in Reference value, the object reference is passed. Object has data type as a reference value. When object are assigned to a new variable, it refers to the same object.
```