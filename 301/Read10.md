# Read 10

## In memory storage

## What is a ‘call’?

The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous. It is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

## How many ‘calls’ can happen at once?

One at a time.

## What does LIFO mean?

Last In, First Out (LIFO)

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
![Call Stack](https://user-images.githubusercontent.com/120413183/224251135-f738b588-2ef8-403e-a9a5-d3a0a11afc63.png)


![Push Pop Top](https://user-images.githubusercontent.com/120413183/224251153-ce8d0ff4-4688-441a-ac7c-0a01b9c500f6.png)

## What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

## What is a ‘reference error’?

The ReferenceError object represents an error when a variable that doesn't exist (or hasn't yet been initialized) in the current scope is referenced.

## What is a ‘syntax error’?

An exception caused by the incorrect use of a pre-defined syntax. Syntax errors are detected while compiling or parsing source code. For example, if you leave off a closing brace ( } ) when defining a JavaScript function, you trigger a syntax error.

## What is a ‘range error’?

A RangeError is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value. This can be encountered when: passing a value that is not one of the allowed string values to String.

## What is a ‘type error’?

The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type.

## What is a breakpoint?

In the debugger window, you can set breakpoints in the JavaScript code. At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).

## What does the word ‘debugger’ do in your code?

The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function. This has the same function as setting a breakpoint in the debugger. If no debugging is available, the debugger statement has no effect.
