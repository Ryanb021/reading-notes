
# Introductory HTML and Javascript

## How the web works

In this topic, it will be explained briefly how Hypertext Transfer Protocol works. But first we'll define what HTTP is.
HTTP: Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other. This is like the language you use to order your goods. [Source](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

When you type a web address into your browser (for our analogy that's like walking to the shop):

The browser goes to the DNS server, and finds the real address of the server that the website lives on (you find the address of the shop).
The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).
The browser assembles the small chunks into a complete web page and displays it to you (the goods arrive at your door — new shiny stuff, awesome!). [Source](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)


## Order in which component files are parsed


When browsers send requests to servers for HTML files, those HTML files often contain <link> elements referencing external CSS stylesheets and <script> elements referencing external JavaScript scripts. It's important to know the order in which those files are parsed by the browser as the browser loads the page:

The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.
As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.
The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it. [Source](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)


## How to find images to add to a website? Just find it on Google images and see what is best for your website. Or if you have your own, upload it on your webpage.
  
## How do you create a String vs a Number in JavaScript
  
In javascript , we can add a number and a number but if we try to add a number and a string then, as addition is not possible, 'concatenation' takes place.

[SOURCE](https://www.tutorialspoint.com/how-to-add-a-number-and-a-string-in-javascript)


## What is a Variable in Javascript?

Variables are used to store data values. It may be used to store a user's email addtess or their name. It can also contain any types of data, such a string, true or false boolean, an object, or a number.


## HTML Attribute

An HTML attribute is a piece of markup language used to adjust the behavior or display of an HTML element. It can be used to change the color, size, or functionality of HTML elements.


## Anatomy of HTML Element [Source](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)


-*The opening tag:* This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.


-*The content:* This is the content of the element. In this example, it is the paragraph text.


-*The closing tag:* This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.


## The difference between Section and Article in HTML elements is, the Article element specifies independent, self contained content. The Sectin element defines section in a document.


## How does metadata influence Search Engine Optimization?


Basically makes it easier for search engines to determine what your content is about.


## How is the meta HTML tag used when specifying metadata?

The *META* tag defines metadata about an HTML document. *META* tags always go inside the *HEAD* element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.
  
  


