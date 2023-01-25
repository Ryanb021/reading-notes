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

Some HTML elements, such as <h1> and <p>, use block as their outer display type by default.

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
