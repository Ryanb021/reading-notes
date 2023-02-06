# Class 11


## Video and audio on the web [Source](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions <video> and <audio> elements and the availability of JavaScript APIs for controlling them. We'll not be looking at JavaScript here — just the basic foundations that can be achieved with HTML.

## The <video> element

The <video> element allows you to embed a video very easily.
  
## src
In the same way as for the <img> element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.

## controls
Users must be able to control video and audio playback (it's especially critical for people who have epilepsy.) You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.

## The paragraph inside the <video> tags
This is called fallback content — this will be displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.
  
## The paragraph inside the <video> tags
This is called *fallback content* — this will be displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.
  
## CSS Grid Layout (aka “Grid” or “CSS Grid”) [Source](https://css-tricks.com/snippets/css/complete-guide-grid/)
  
It is a two-dimensional grid-based layout system that, compared to any web layout system of the past, completely changes the way we design user interfaces. CSS has always been used to layout our web pages, but it’s never done a very good job of it. First, we used tables, then floats, positioning and inline-block, but all of these methods were essentially hacks and left out a lot of important functionality (vertical centering, for instance). Flexbox is also a very great layout tool, but its one-directional flow has different use cases — and they actually work together quite well! Grid is the very first CSS module created specifically to solve the layout problems we’ve all been hacking our way around for as long as we’ve been making websites.
  
## Grid Container
The element on which display: grid is applied. It’s the direct parent of all the grid items.  In this example container is the grid container.
  
![container](https://user-images.githubusercontent.com/120413183/216897023-0e738e3c-85b3-4c4b-a088-0fbca3354fd5.png)

## Grid Item
The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.
  
![item](https://user-images.githubusercontent.com/120413183/216897121-c908fd70-6b2b-4128-a438-1f6931b0d239.png)

Grid Line
The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.
  
![line](https://user-images.githubusercontent.com/120413183/216897187-a5e0e896-3e03-49ba-99d6-676967fbb584.png)

Grid Cell
The space between two adjacent row and two adjacent column grid lines. It’s a single “unit” of the grid. Here’s the grid cell between row grid lines 1 and 2, and column grid lines 2 and 3.
  
![cell](https://user-images.githubusercontent.com/120413183/216897250-b7389ef9-be4b-44cf-8b0c-bb302ff1b08f.png)

Grid Track
The space between two adjacent grid lines. You can think of them as the columns or rows of the grid. Here’s the grid track between the second and third-row grid lines.
  
![track](https://user-images.githubusercontent.com/120413183/216897309-37b48b48-ac5d-4780-84b5-745a44bd90f8.png)

Grid Area
The total space surrounded by four grid lines. A grid area may be composed of any number of grid cells. Here’s the grid area between row grid lines 1 and 3, and column grid lines 1 and 3.
  
![Area](https://user-images.githubusercontent.com/120413183/216897352-d6b81241-980c-451a-ae95-2cd7da6f2da3.png)
  
## Responsive Images
   
Responsive image technologies were implemented recently to solve the problems by letting you offer the browser several image files, either all showing the same thing but containing different numbers of pixels (resolution switching), or different images suitable for different space allocations (art direction).

## The <img> HTML element embeds an image into the document.

-The src attribute is required, and contains the path to the image you want to embed.

-The alt attribute holds a text description of the image, which isn't mandatory but is incredibly useful for accessibility — screen readers read this description out to their users so they know what the image means. Alt text is also displayed on the page if the image can't be loaded for some reason: for example, network errors, content blocking, or linkrot.
  
## srcset
One or more strings separated by commas, indicating possible image sources for the user agent to use. Each string is composed of:

-A URL to an image

-Optionally, whitespace followed by one of:

  -A width descriptor (a positive integer directly followed by w). The width descriptor is divided by the source size given in the sizes attribute to calculate the effective pixel density.
  
  -A pixel density descriptor (a positive floating point number directly followed by x).
  
## sizes
One or more strings separated by commas, indicating a set of source sizes. Each source size consists of:

-A media condition. This must be omitted for the last item in the list.

-A source size value.
[Source](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)
