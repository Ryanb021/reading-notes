# Class 8

## Flexbox [Source](https://web.dev/learn/css/flexbox/#what-can-you-do-with-a-flex-layout)

Flexbox is a layout mechanism designed for laying out groups of items in one dimension. It is a layout model designed for one-dimensional content. It excels at taking a bunch of items which have different sizes, and returning the best layout for those items.

## The main axis and the cross axis #

The key to understanding flexbox is to understand the concept of a main axis and a cross axis. The main axis is the one set by your flex-direction property. If that is row your main axis is along the row, if it is column your main axis is along the column.
Flex items move as a group on the main axis. Remember: we've got a bunch of things and we are trying to get the best layout for them as a group.

![Main Axis](https://user-images.githubusercontent.com/120413183/216205633-5bee7596-d9f1-41f4-9a1f-fe827d4595dd.png)

The cross axis runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column.

![Cross Axis](https://user-images.githubusercontent.com/120413183/216205661-88c226b9-0e33-47d8-bdb6-78ec529f9c01.png)

You can do two things on the cross axis. You can move the items individually or as a group, so they align against each other and the flex container. Also, if you have wrapped flex lines, you can treat those lines as a group to control how space is assigned to those lines. You will see how this all works in practice throughout this guide, for now just keep in mind that the main axis follows your flex-direction.

You should be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The row-reverse and column-reverse values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.

## Why Flexbox? [Source](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

For a long time, the only reliable cross-browser compatible tools available for creating CSS layouts were features like floats and positioning. These work, but in some ways they're also limiting and frustrating.

The following simple layout designs are either difficult or impossible to achieve with such tools in any kind of convenient, flexible way:

-Vertically centering a block of content inside its parent.

-Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.

-Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

## flex: shorthand versus longhand

flex is a shorthand property that can specify up to three different values:

The unitless proportion value we discussed above. This can be specified separately using the flex-grow longhand property.
A second unitless proportion value, flex-shrink, which comes into play when the flex items are overflowing their container. This value specifies how much an item will shrink in order to prevent overflow. This is quite an advanced flexbox feature and we won't be covering it any further in this article.
The minimum size value we discussed above. This can be specified separately using the flex-basis longhand value.
We'd advise against using the longhand flex properties unless you really have to (for example, to override something previously set). They lead to a lot of extra code being written, and they can be somewhat confusing.
