# Class 3


## The *Unordered List* element represents an unordered list of items, typically rendered as a bulleted list. It is used for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Typically, unordered-list items are displayed with a bullet, which can be of several forms, like a dot, a circle, or a square. The bullet style is not defined in the HTML description of the page, but in its associated CSS, using the list-style-type property.

## The *Ordered List* element represents an ordered list of items — typically rendered as a numbered list. Typically, ordered list items display with a preceding marker, such as a number or letter. The *ordered list and *unordered list* elements may nest as deeply as desired, alternating between them however you like. [Source](https://github.com/Ryanb021/reading-notes/edit/main/201/Read03.md)

## *NOTE:* By *NESTING* a list, the bullet style will change for the unordered list. Use the unordered list if grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Use ordered list if the order is meaningful such as recipe steps, turn by turn directions, instruction on repairing or performing maintenance to an equipment.


## Ways you can change the numbers on list items provided by an ordered list [Source](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

-a for lowercase letters

-A for uppercase letters

-i for lowercase Roman numerals

-I for uppercase Roman numerals

-1 for numbers (default)


## Padding and Margin [Source](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

*If a box has an outer display type of block, then:*

-The box will break onto a new line.

-The width and height properties are respected.

-Padding, margin and border will cause other elements to be pushed away from the box.

-The box will extend in the inline direction to fill the space available in its container. In most cases, the box will become as wide as its container, filling up 100% of the space available.

Some HTML elements, such as *h1* and *p*, use block as their outer display type by default.

*If a box has an outer display type of inline, then:*

-The box will not break onto a new line.
  
-The width and height properties will not apply.
  
-Vertical padding, margins, and borders will apply but will not cause other inline boxes to move away from the box.
  
-Horizontal padding, margins, and borders will apply and will cause other inline boxes to move away from the box.
  
 
 ##  Four parts of an HTML elements box
  
-*Content box:*
  
The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
  
-*Padding box:*
  
The padding sits around the content as white space; size it using padding and related properties.
  
-*Border box:*
  
The border box wraps the content and any padding; size it using border and related properties.
  
-*Margin box:*
  
The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.


## What is an array?

Arrays are generally described as "list-like objects"; they are basically single objects that contain multiple values stored in a list. Array objects can be stored in variables and dealt with in much the same way as any other type of value, the difference being that we can access each value inside the list individually, and do super useful and efficient things with the list, like loop through it and do the same thing to every value. Maybe we've got a series of product items and their prices stored in an array, and we want to loop through them all and print them out on an invoice, while totaling all the prices together and printing out the total price at the bottom.

If we didn't have arrays, we'd have to store every item in a separate variable, then call the code that does the printing and adding separately for each item. This would be much longer to write out, less efficient, and more error-prone. [Source](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)

## Things
