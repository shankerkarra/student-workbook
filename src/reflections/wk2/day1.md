## What is Scope?
Scope is accessbile limitation on a variable, function or object.
## What is Hoisting?
Javascript engine created global eecution context and has two phases: Creation and Excution.

IN the creation phase, javascript treats variables and functions declarations to the top of the code and these feature is called as Hoisting in JAvascript.g in JavaScript.

## In what cases might you use let vs const vs var?

var: 
When declared outside of the function, it is treated as GLobal and when the same var is declared in function; its scope is lost right after the function is completed.

Let: 
Let is improvised version of var and it is scope is blocked. Let can be re-assigned; but cannot be declared again.

const:
Const is simliar to let; but cannot be upated or re-created; but its properties can be updated.

var and let can be declared without initialization, whereas const mist be initialized, during decalarations.

Lab work URL : https://shankerkarra.github.io/js-tests-basics/