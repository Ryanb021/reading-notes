# Class 7

## Domain Modeling [Source](https://github.com/codefellows/domain_modeling#domain-modeling)

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

## Here's some tips to follow when building your own domain models.

-When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

-Model its attributes with a constructor function that defines and initializes properties.

-Model its behaviors with small methods that focus on doing one job well.

-Create instances using the new keyword followed by a call to a constructor function.

-Store the newly created object in a variable so you can access its properties and methods from outside.

-Use the this variable within methods so you can access the object's properties and methods from inside.

## What is a table? [Source](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

A table is a structured set of data made up of rows and columns (tabular data). A table allows you to quickly and easily look up values that indicate some kind of connection between different types of data, for example a person and their age, or a day of the week. The point of a table is that it is rigid. Information is easily interpreted by making visual associations between row and column headers. When implemented correctly, HTML tables are handled well by accessibility tools such as screen readers, so a successful HTML table should enhance the experience of sighted and visually impaired users alike.

## Introducing constructors

Using object literals is fine when you only need to create one object, but if you have to create more than one, as in the previous section, they're seriously inadequate. We have to write out the same code for every object we create, and if we want to change some properties of the object - like adding a height property - then we have to remember to update every object.

We would like a way to define the "shape" of an object — the set of methods and the properties it can have — and then create as many objects as we like, just updating the values for the properties that are different. Constructors, by convention, start with a capital letter and are named for the type of object they create.

## Object Prototypes [Source](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object_prototypes)

Prototypes are the mechanism by which JavaScript objects inherit features from one another. Every object in JavaScript has a built-in property, which is called its prototype. The prototype is itself an object, so the prototype will have its own prototype, making what's called a prototype chain. The chain ends when we reach a prototype that has null for its own prototype. When you try to access a property of an object: if the property can't be found in the object itself, the prototype is searched for the property. If the property still can't be found, then the prototype's prototype is searched, and so on until either the property is found, or the end of the chain is reached, in which case undefined is returned.

## Setting a prototype

There are various ways of setting an object's prototype in JavaScript, and here we'll describe two: Object.create() and constructors.

## Using Object.create

The Object.create() method creates a new object and allows you to specify an object that will be used as the new object's prototype.

## Using a constructor

In JavaScript, all functions have a property named prototype. When you call a function as a constructor, this property is set as the prototype of the newly constructed object (by convention, in the property named __proto__).

So if we set the prototype of a constructor, we can ensure that all objects created with that constructor are given that prototype.

## Using a constructor

In JavaScript, all functions have a property named prototype. When you call a function as a constructor, this property is set as the prototype of the newly constructed object (by convention, in the property named __proto__).

So if we set the prototype of a constructor, we can ensure that all objects created with that constructor are given that prototype.

## Prototypes and inheritance

Prototypes are a powerful and very flexible feature of JavaScript, making it possible to reuse code and combine objects.

In particular they support a version of inheritance. Inheritance is a feature of object-oriented programming languages that lets programmers express the idea that some objects in a system are more specialized versions of other objects.

For example, if we're modeling a school, we might have professors and students: they are both people, so have some features in common (for example, they both have names), but each might add extra features (for example, professors have a subject that they teach), or might implement the same feature in different ways. In an OOP system we might say that professors and students both inherit from people.

You can see how in JavaScript, if Professor and Student objects can have Person prototypes, then they can inherit the common properties, while adding and redefining those properties which need to differ.

In the next article we'll discuss inheritance along with the other main features of object-oriented programming languages, and see how JavaScript supports them.
