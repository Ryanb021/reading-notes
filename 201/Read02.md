# Class 2


## Importance of Semantics and why do we need it [Source](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

Semantics are relied on everywhere around us—we rely on previous experience to tell us what the function of an everyday object is; when we see something, we know what its function will be. So, for example, we expect a red traffic light to mean "stop," and a green traffic light to mean "go." Things can get tricky very quickly if the wrong semantics are applied. (Do any countries use red to mean "go"? We hope not.). In a similar vein, we need to make sure we are using the correct elements, giving our content the correct meaning, function, or appearance.

## How many levels of headings are there in HTML?

HTML defines six levels of headings. A heading element implies all font changes, paragraph breaks before and after, and any white spaces necessary to render the heading. The heading elements are H1, H2, H3, H4, H5, and H6 with H1 being the highest (or most important) level and H6 the least. [Source](ww.w3.org)

## Subscript

The sub tag is used to add a subscript text to the HTML document. The sub tag defines the subscript text. Subscript text appears half a character below the normal line and is sometimes rendered in a smaller font.

## Superscript

The sup tag is used to add a superscript text the HTML document. The sup tag defines the superscript text. SUperscript text appears half a character above the normal line and is sometimes rendered in a smaller font. Superscript can be used for footnotes.

[Source](geeksforgeeks.org)

## When using *abbr* tag element, use the global *title* element to provide full expansion of the term.


## Ways we can apply CSS to HTML

*External stylesheet*

An external stylesheet contains CSS in a separate file with a .css extension. This is the most common and useful method of bringing CSS to a document. You can link a single CSS file to multiple web pages, styling all of them with the same CSS stylesheet.


*Internal stylesheet*

An internal stylesheet resides within an HTML document. To create an internal stylesheet, you place CSS inside a <style> element contained inside the HTML *head*. In some circumstances, internal stylesheets can be useful. For example, perhaps you're working with a content management system where you are blocked from modifying external CSS files. But for sites with more than one page, an internal stylesheet becomes a less efficient way of working. To apply uniform CSS styling to multiple pages using internal stylesheets, you must have an internal stylesheet in every web page that will use the styling. The efficiency penalty carries over to site maintenance too. With CSS in internal stylesheets, there is the risk that even one simple styling change may require edits to multiple web pages.
  
*Inline styles*
  
Inline styles are CSS declarations that affect a single HTML element, contained within a style attribute.

*Avoid using inline styles inside the HTML document. It is the opposite of a best practice. First, it is the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website.*

*There are a few circumstances where inline styles are more common. You might have to resort to using inline styles if your working environment is very restrictive. For example, perhaps your CMS only allows you to edit the HTML body. You may also see a lot of inline styles in HTML email to achieve compatibility with as many email clients as possible.* [Source](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)
  
## Javascript
  
JavaScript is a powerful programming language that can add interactivity to a website. It was invented by Brendan Eich. JavaScript is versatile and beginner-friendly. With more experience, you'll be able to create games, animated 2D and 3D graphics, comprehensive database-driven apps, and much more! JavaScript itself is relatively compact, yet very flexible. Developers have written a variety of tools on top of the core JavaScript language, unlocking a vast amount of functionality with minimum effort. [Source](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
  
## Operators

An operator is a mathematical symbol that produces a result based on two values (or variables). In the following table, you can see some of the simplest operators, along with some examples to try in the JavaScript console.
  
*Addition*
  
Add two numbers together or combine two strings using the + symbol.
  
*Subtraction, Multiplication, Division*
  
These do what you'd expect them to do in basic math using the symbols -, * , /
  
*Assignment*
  
Assigns a value to a variable using the symbol =
  
*Strict Equality*
  
This performs a test to see if two values are equal. It returns a true/false (Boolean) result using the symbol ===

*Not, Does-not-equal*
  
This returns the logically opposite value of what it precedes. It turns a true into a false, etc.. When it is used alongside the Equality operator, the negation operator tests whether two values are not equal using the symbols !, !==
[Source](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

#Examples of Comparison Operators
  
Strict equality ===
  
Strict-non-equality !==
  
Less than <
  
Greater than >
  
Less than or equal to <=
  
Greater than or equal to >=
  
## In Javascript we have the following conditional statements. Use *if* to specify a block of code to be excuted, if a specified condition is true. Use *else* to specify a block of code to be executed, if the same condition is false. Use *else if* to specify a new condition to test, if the first condtiion is false.

