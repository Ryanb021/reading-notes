# Class 12

## Introduction to the HTML5 Canvas element [Source](https://www.javascripttutorial.net/web-apis/javascript-canvas/)

HTML5 features the <canvas> element that allows you to draw 2D graphics using JavaScript.
  
![canvas 1](https://user-images.githubusercontent.com/120413183/217305456-0bca5a7e-4774-44cd-a301-e10d29f544e6.png)

The <canvas> element requires at least two attributes: width and height that specify the size of the canvas:
  
![canvas 2](https://user-images.githubusercontent.com/120413183/217305568-4c379319-d0ef-4503-8759-af717cbfb8ed.png)
  
Like other elements, you can access the width and height properties of the <canvas> element via its DOM properties:
  
![canvas 3](https://user-images.githubusercontent.com/120413183/217305595-f60a83e2-8d3a-44a7-84fa-065ca05e547b.png)

## Fallback content
  
Unlike the <img> element, The <canvas> element requires the closing tag </canvas>. Any content between the opening and closing tags is fallback content that will display only if the browser doesn’t support the <canvas> element. For example:
  
![canvas 1](https://user-images.githubusercontent.com/120413183/217306266-c1b1c326-5dcc-46cb-8412-585c20763f4b.png)

Nowadays, most modern web browsers support the <canvas> element.
  
## The rendering context
  
Initially, the canvas is blank. To draw something, you need to access the rendering context and use it to draw on the canvas.

The <canvas> element features the getContext() method that returns a render context object.

The getContext() takes one argument which is the type of context. For example, you use the "2d" to get a 2D rendering context object, which is an instance of the CanvasRenderingContext2D interface.

The 2D rendering context allows you to draw shapes, text, images, and other objects.

The following example shows how to select the canvas element using the querySelector() method and access the drawing context by calling its getContext() method:
  
![canvas 2](https://user-images.githubusercontent.com/120413183/217307054-94d5a983-a078-4fe1-b8ea-aeec6a43569c.png)

Check for canvas support
When using the <canvas> element, it’s important to check if the browser supports the getContext() method. To do it, you use the following code:
  
![canvas 3](https://user-images.githubusercontent.com/120413183/217307166-02e6733c-800d-43eb-a4fa-ccf7272b04fc.png)

## Chart.JS [Source](https://www.chartjs.org/docs/latest/)
Chart.js provides a set of frequently used chart types, plugins, and customization options. In addition to a reasonable set of built-in chart types, you can use additional community-maintained chart types . On top of that, it’s possible to combine several chart types into a mixed chart (essentially, blending multiple chart types into one on the same canvas).

Chart.js is highly customizable with custom plugins to create annotations, zoom, or drag-and-drop functionalities to name a few things.

## Defaults
Chart.js comes with a sound default configuration, making it very easy to start with and get an app that is ready for production. Chances are you will get a very appealing chart even if you don’t specify any options at all. For instance, Chart.js has animations turned on by default, so you can instantly bring attention to the story you’re telling with the data.

## Integrations
Chart.js comes with built-in TypeScript typings and is compatible with all popular JavaScript frameworks including React , Vue , Svelte , and Angular . You can use Chart.js directly or leverage well-maintained wrapper packages that allow for a more native integration with your frameworks of choice.

## Developer experience
Chart.js has very thorough documentation (yes, you're reading it), API reference, and examples. Maintainers and community members eagerly engage in conversations on Slack , GitHub Discussions , and Stack Overflow where more than 11,000 questions are tagged with chart.js.

## Canvas rendering
Chart.js renders chart elements on an HTML5 canvas unlike several other, mostly D3.js-based, charting libraries that render as SVG. Canvas rendering makes Chart.js very performant, especially for large datasets and complex visualizations that would otherwise require thousands of SVG nodes in the DOM tree. At the same time, canvas rendering disallows CSS styling, so you will have to use built-in options for that, or create a custom plugin or chart type to render everything to your liking.

## Performance
Chart.js is very well suited for large datasets. Such datasets can be efficiently ingested using the internal format so you can skip data parsing and normalization. Alternatively, data decimation can be configured to sample the dataset and reduce its size before rendering.

In the end, the canvas rendering that Chart.js uses reduces the toll on your DOM tree in comparison to SVG rendering. Also, tree-shaking support allows you to include minimal parts of Chart.js code into your bundle, reducing bundle size and page load time.

## Community
Chart.js is actively developed and maintained by the community. With minor releases on an approximately bi-monthly basis and major releases with breaking changes every couple of years, Chart.js keeps the balance between adding new features and making it a hassle to keep up with them.
  
## 3 different Chart types you can create using Chart.js
  
-Area Chart

-Bar Chart
  
-Bubble Chart
  
## What are some advantages to displaying data via a chart over a table?

Charts are most useful when the data you are presenting is quantitative and has fewer distinct axes to measure. More importantly, charts can show you the “shape” of data—patterns that emerge when the data is examined altogether instead of presented in sets of individual values.

## How could Chart.js aid your previously created applications visually?
  
It can make projects and assignments more presentable and easier to explain and understand.
  

