# Class 5


## How do we put an image on a webpage?

In order to put a simple image on a web page, we use the <img> element. This is a void element (meaning, it cannot have any child content and cannot have an end tag) that requires two attributes to be useful: src and alt. The src attribute contains a URL pointing to the image you want to embed in the page. As with the href attribute for <a> elements, the src attribute can be a relative URL or an absolute URL. Without a src attribute, an img element has no image to load.
  
## What exactly should you write inside your alt attribute? It depends on why the image is there in the first place. In other words, what you lose if your image doesn't show up:

-Decoration. You should use CSS background images for decorative images, but if you must use HTML, add a blank alt="". If the image isn't part of the content, a screen reader shouldn't waste time reading it.
  
-Content. If your image provides significant information, provide the same information in a brief alt text – or even better, in the main text which everybody can see. Don't write redundant alt text. How annoying would it be for a sighted user if all paragraphs were written twice in the main content? If the image is described adequately by the main text body, you can just use alt="".
  
-Link. If you put an image inside *a* tags, to turn an image into a link, you still must provide accessible link text. In such cases you may, either, write it inside the same <a> element, or inside the image's alt attribute – whichever works best in your case.
  
-Text. You should not put your text into images. If your main heading needs a drop shadow, for example, use CSS for that rather than putting the text into an image. However, If you really can't avoid doing this, you should supply the text inside the alt attribute.
  
Essentially, the key is to deliver a usable experience, even when the images can't be seen. This ensures all users are not missing any of the content. Try turning off images in your browser and see how things look. You'll soon realize how helpful alt text is if the image cannot be seen.
  
## CSS first steps
  
*CSS (Cascading Style Sheets)*

Is used to style and layout web pages — for example, to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features. This module provides a gentle beginning to your path towards CSS mastery with the basics of how it works, what the syntax looks like, and how you can start using it to add styling to HTML.

*CSS building blocks*
 
This module carries on where CSS first steps left off — now you've gained familiarity with the language and its syntax, and got some basic experience with using it, it's time to dive a bit deeper. This module looks at the cascade and inheritance, all the selector types we have available, units, sizing, styling backgrounds and borders, debugging, and lots more.

The aim here is to provide you with a toolkit for writing competent CSS and help you understand all the essential theory, before moving on to more specific disciplines like text styling and CSS layout.

*CSS styling text*
  
With the basics of the CSS language covered, the next CSS topic for you to concentrate on is styling text — one of the most common things you'll do with CSS. Here we look at text styling fundamentals, including setting font, boldness, italics, line and letter spacing, drop shadows, and other text features. We round off the module by looking at applying custom fonts to your page, and styling lists and links.

*CSS layout*
  
At this point, we've already looked at CSS fundamentals, how to style text, and how to style and manipulate the boxes that your content sits inside. Now it's time to look at how to place your boxes in the right place with respect to the viewport, and one another. We have covered the necessary prerequisites so we can now dive deep into CSS layout, looking at different display settings, modern layout tools like flexbox, CSS grid, and positioning, and some of the legacy techniques you might still want to know about.

*Solving common CSS problems*
Use CSS to solve common problems provides links to sections of content explaining how to use CSS to solve very common problems when creating a web page.

From the beginning, you'll primarily apply colors to HTML elements and their backgrounds; change the size, shape, and position of elements; and add and define borders on elements. But there's not much you can't do once you have a solid understanding of even the basics of CSS. One of the best things about learning CSS is that once you know the fundamentals, usually you have a pretty good feel for what can and can't be done, even if you don't know how to do it yet! [Source](https://developer.mozilla.org/en-US/docs/Learn/CSS)
