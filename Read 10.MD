# From the Duckett JS book:

## JavaScript book, Ch. 10, pg 450 - 486 “Error Handling & Debugging”
- understanding execution contexts and stacks is important for debugging
- Execution Context
    1) global context
    2) function context
    3) eval context
- Variable Scope
    1) global scope
    2) function-level scope
- the stack
- hoisting
    - variables and functions within each execution context are created before  they are executed
- debugging is process of finding errors
- errors create error objects with
    - name - type of error
    - message - description
    - filenumber - name of Javascript file
    - linenumber of error
- use the console to narrow down where the error occurs
- debugging workflow
    - where is problem
    - what is the problem
- use console.log() to view data in the console
- use breakpoints to stop the execution of code on any line
- use devtools to step through the code line by line
- debugger is a keyword used to create a breakpoint in the code
- JavaScript has 7 types of errors