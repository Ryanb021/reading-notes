# Read 09

## Functional Programming

## What is functional programming?

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

## What is a pure function and how do we know if something is a pure function?

Pure Functions returns the same result if given the same arguments (it is also referred as deterministic) and it does not cause any observable side effects. Using only pure functions can remove a lot of bugs.

## What are the benefits of a pure function?

Using only pure functions can remove a lot of bugs

## What is immutability?

An immutable value or object cannot be changed, so every update creates new value, leaving the old one untouched. For example, if your application state is immutable, you can save all the state objects in a single store to easily implement functionality to undo and redo.

## What is Referential transparency?

Referential transparency is the ability to replace an expression with its result, without changing the meaning/behavior of the program. It is a property of expressions, which applies to pure functions, since these functions are essentially parametrized expressions.

## What is a module?

Is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. js application. Each module in Node. js has its own context, so it cannot interfere with other modules or pollute global scope.

## What does the word ‘require’ do?

In NodeJS, require() is a built-in function to include external modules that exist in separate files. require() statement basically reads a JavaScript file, executes it, and then proceeds to return the export object.

## How do we bring another module into the file the we are working in?

To include functions defined in another file in Node. js, we need to import the module. we will use the require keyword at the top of the file. The result of require is then stored in a variable which is used to invoke the functions using the dot notation.

## What do we have to do to make a module available?

 To use external modules in our application first, we need to install the external module codebase from NPM locally using Npm install module_name command.
