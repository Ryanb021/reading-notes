# Read 03

## Passing Functions as Props

## Lists and Keys

## What does .map() return?

JSX elements

## If I want to loop through an array and display each value in JSX, how do I do that in React?

To loop an array and display each value in JSX, use curly brackets {}.

## Each list item needs a unique ____.

Key/s

## What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity. The spread operator was added to JavaScript in ES6 (ES2015), just like the rest parameters, which have the same syntax: three magic dots ….

## The Spread Operator

## What is the spread operator?

Spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments. 

## List 4 things that the spread operator can do.

- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments

## Give an example of using the spread operator to combine two arrays.

![combining array](https://user-images.githubusercontent.com/120413183/222050186-65384b55-a4f8-4099-9894-bd9696e175b4.png)

## Give an example of using the spread operator to add a new item to an array.

![adding items](https://user-images.githubusercontent.com/120413183/222050480-6898968a-d9df-4e68-a350-3397f0a9ec50.png)

## Give an example of using the spread operator to combine two objects into one.

![combining 2 items into 1](https://user-images.githubusercontent.com/120413183/222050641-24c5d69d-dac5-4816-aa80-824d899af5ed.png)

## How to pass Functions between Components

## In the video, what is the first step that the developer does to pass functions between components?

Increment

## In your own words, what does the increment function do?

The increment  operator increments (adds one to) its operand and returns the value before or after the increment, depending on where the operator is placed.

## How can you pass a method from a parent component into a child component?

Increment={this.increment} on the child component.

## How does the child component invoke a method that was passed to it from a parent component?

Call that method in the childt with this.props.increment(this.props.whatever is being passed).
