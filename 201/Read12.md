# Class 12

## Introduction to the HTML5 Canvas element

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
