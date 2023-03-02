# Read 04

## Readings: React and Forms [Source](https://reactjs.org/docs/forms.html)

## What is a ‘Controlled Component’?

In HTML, form elements such as input, textarea, and select typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState(). We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

We should wait to store users responses from the form into the state when they submit the form. Reason is, if we update the state with their responses as soon as they enter them, we can’t provide instant validation on the field as the user types, nor can we do things like enforce a custom input format, conditionally show or hide form elements, or disable/enable the submit button. That is called *Uncontrolled Inputs*. Whereas, if we wait to store users responses from the form into the state when they submit the form, we have a lot of control over the input/response, as we can react to changes to the value on the fly. This is called *Controlled Inputs.* Because of this, controlled inputs don’t suffer from the limitations of uncontrolled ones, opening up to following possibilities such as instant input validation, instant input foramtting, conditionally disable form submission, and dynamically generate new inputs.

## How do we target what the user is entering if we have an event handler on an input field?

Add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

## The Conditional (Ternary) Operator Explained

## Why would we use a ternary operator?

It makes the code shorter yielding the same results.
