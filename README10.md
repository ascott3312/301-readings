#  THE CALL STACK
- A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

-- When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
-- Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
-- When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
-- If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

## JavaScript
- The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.
- LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
- What causes a stack overflow?
1. A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

### Error Messages

1. Reference errors
- This is as simple as when you try to use a variable that is not yet declared you get this type os errors.
1. Syntax errors
- I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax,
1. Range errors
1. Type errors