# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
CREATE, READ, UPDATE, DELETE

```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
CREATE - POST
READ - GET
UPDATE - PUT
DELETE - DELETE
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
ORM stands for Object Relation Mapping. TypeORM is used for interacting with MOngoDB.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
POST and PUT 
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```

Synchronous - Asynchronous

```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import defaultExport from module
 or 
import {single Export} from module

import {multiple export ( from the same module)} from module

let schema = mongoose.schema 
(short reference to the mongoose Schema; the short reference, which can be used to created new instances)
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```

Middleware is a software code that can interacts as bridge with other applications, databases, tools.

```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
Request  - Response
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
http://url/?tag:winter

```