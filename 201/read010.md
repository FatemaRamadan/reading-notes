## Chapter 10 : Error Handling and Debugging

- in order to find an Error best thing is to follow the **Order of Execution**
- by knowing how the script is processed and step it needs to work we might be able to find error.
- we have Execuation context ,where statments live in either a Global context or a function context
- we have variable scope ,where we find Globale scope that can be used any where in the code and a Function level scope.
- The stack:when statment needs a data from another function it **Stacks** or **pile** the new function on the top of the current task.
- every time time when a new item is added to stack it creates a *new execuation context* it has two phases:
  1. Prepare; a new scoop is created as well as Variables and functions and argument.the `this` value has been determined.
  2.Execut, now it can assign values to variables and run the code and excute sataments.
 - previouly we learned we van call a function befor its being decalred
   onley in function declration not function expression, also we can assign a value to 
   a variable before its declration.
- each execuation can access its parents variable object.
- Lexical scope, when functions are linked to the object they were defined with.

- understanding errors
- when JS generates an error it throws an exception.then the interprter stops and looks for exception-handling code.
- Error objects help find mistakes and browser have tools to help read them.
- when error object is created it will contain:
  
 Proparity|Description
 ---------|---------
name |Type of excuation
message | description
fileNumber |Name of JS file
lineNumber| line number error

- there are 7 types of built-in errors in objects like syntax-error,ReferanceError,TypeError.
- SynatxError : its caused by incorect use of language rules like `'` or `;` or a missing closing tag.....etc
-ReferenceError: Variablesare either not declared or out of scope.
- URIError: when using charechters that are not escaped. like ( / ? & # : ;).
- EvalError: when using eval() function.
- TypeError: when using a value with an expected datatype.
- rangeError: when number is outside of range.

- How to deal with errors :
1. debug the script to fix the error, using tools to retrace the errors
2. Handle the error. we can use `try, catch, throw.finally` statments .

-Debugging workflow
- in order to find the proble we have to *Find where is the problem * 
  then define *what exactly is the problem* ?
- JS console tells us where the problem is and whaty kind of isssue it seems to be.
- consoles are used in diffrent web browsers such as Chrom and IE and firefox,we
  can write in the console to get result and we can write cosole in the code to show the outcome.
- we can use `console.table() ` to output table showing its objects and arrays.
- `console.assert()` can test for condidtions and write to console onley if expression is false.
- breakpoints; to stop the excution of a code at any point; in order to check the values used in that point .
-Stepping through code; when we have breakpoints the debugger let us go through the code line by line.
- we can creat breakPoints using `debugger` kwyword.
- if we knew that the code might fail , we can use `try,catch,finally` 
- if we knew something may cause problem we can generate our own errors befor the interpreter creates them.
 



