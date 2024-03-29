# Class 9

## Forms [Source](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form) [Source](https://developer.mozilla.org/en-US/docs/Learn/Forms) [Source](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

## What are web forms?
Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data later in the module), or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

A web form's HTML is made up of one or more form controls (sometimes called widgets), plus some additional elements to help structure the overall form — they are often referred to as HTML forms. The controls can be single or multi-line text fields, dropdown boxes, buttons, checkboxes, or radio buttons, and are mostly created using the <input> element, although there are some other elements to learn about too.

Form controls can also be programmed to enforce specific formats or values to be entered (form validation), and paired with text labels that describe their purpose to both sighted and visually impaired users.

Web forms are a very powerful tool for interacting with users — most commonly they are used for collecting data from users, or allowing them to control a user interface. However, for historical and technical reasons, it's not always obvious how to use them to their full potential. Mastering forms however requires more than just HTML knowledge — you also need to learn some specific techniques to style form controls, and some scripting knowledge is required to handle things like validation and creating custom form controls.

The above text is a good indicator as to why we've put web forms into its own standalone module, rather than trying to mix bits of it into the HTML, CSS, and JavaScript topic areas — form elements are more complex than most other HTML elements, and they also require a close marriage of related CSS and JavaScript techniques to get the most out of them.


## When designing a form, what are some key things to keep in mind when it comes to user experience?
From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.


## The *form* element

This element formally defines a form. It's a container element like a <section> or <footer> element, but specifically for containing forms; it also supports some specific attributes to configure the way the form behaves. All of its attributes are optional, but it's standard practice to always set at least the action and method attributes:

The action attribute defines the location (URL) where the form's collected data should be sent when it is submitted.
The method attribute defines which HTTP method to send the data with (usually get or post).
  
## The *label* *input* and *textarea* elements

The input field for the name is a single-line text field.
The input field for the email is an input of type email: a single-line text field that accepts only email addresses.
The input field for the message is a <textarea>; a multiline text field.
  
## The *button* element
The markup for our form is almost complete; we just need to add a button to allow the user to send, or "submit", their data once they have filled out the form. This is done by using the <button> element.

The <button> element also accepts a type attribute — this accepts one of three values: submit, reset, or button.

A click on a submit button (the default value) sends the form's data to the web page defined by the action attribute of the <form> element.
A click on a reset button resets all the form widgets to their default value immediately. From a UX point of view, this is considered bad practice, so you should avoid using this type of button unless you really have a good reason to include one.
A click on a button button does nothing! That sounds silly, but it's amazingly useful for building custom buttons — you can define their chosen functionality with JavaScript.
  
## Events
  
Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them.

For example, if the user clicks a button on a webpage, you might want to react to that action by displaying an information box. In this article, we discuss some important concepts surrounding events, and look at how they work in browsers.
  
## A series of fortunate events

As mentioned above, events are actions or occurrences that happen in the system you are programming — the system produces (or "fires") a signal of some kind when an event occurs, and provides a mechanism by which an action can be automatically taken (that is, some code running) when the event occurs. Events are fired inside the browser window, and tend to be attached to a specific item that resides in it. This might be a single element, a set of elements, the HTML document loaded in the current tab, or the entire browser window. There are many different types of events that can occur.
  
For example:

-The user selects, clicks, or hovers the cursor over a certain element.

-The user chooses a key on the keyboard.

-The user resizes or closes the browser window.

-A web page finishes loading.
  
-A form is submitted.
  
-A video is played, paused, or ends.
  
-An error occurs.
  
-You can gather from this (and from glancing at the MDN event reference) that there are a lot of events that can be fired.
  

To react to an event, you attach an event handler to it. This is a block of code (usually a JavaScript function that you as a programmer create) that runs when the event fires. When such a block of code is defined to run in response to an event, we say we are registering an event handler. Note: Event handlers are sometimes called event listeners — they are pretty much interchangeable for our purposes, although strictly speaking, they work together. The listener listens out for the event happening, and the handler is the code that is run in response to it happening. [Source](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
