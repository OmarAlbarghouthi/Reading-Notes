# **Docs for the HTML <**canvas**> Element & Chart.js**


## **What is use of canvas?**

<**canvas**> is an HTML element which can be used to draw graphics via scripting (usually JavaScript). This can, for instance, be used to draw graphs, combine photos, or create simple (and not so simple) animations. ... This tutorial describes how to use the <canvas> element to draw 2D graphics, starting with the basics.


## **What are the different types of canvas?**

**Types of canvases**

Canvases are available in various forms to suit different applications and budgets. The main types are stretched canvas, canvas panels, canvas pads, and canvas rolls.

___

# **Drawing shapes with canvas**


## **What is Canvas Sahpe?**
Shaped canvases are paintings that depart from the normal flat, rectangular configuration. Canvases may be shaped by altering their outline, while retaining their flatness

Unlike SVG, <**canvas**> only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.

## **How do you make a triangle in canvas?**
 
Move your virtual pen to to the **x and y** co-ordinate where you wish to start drawing the triangle. With your virtual pen at the starting point, use the lineTo method to draw lines between two points. **Specify the fill color, line color / thickness, etc.** to adjust how your triangle looks.


## **Can we draw circle in canvas?**

To draw a circle on a canvas, use the following methods: beginPath() - begins a path. arc(x,y,r,startangle,endangle) - creates an arc/curve. To create a circle with arc(): Set start angle to 0 and end angle to 2*Math.
___________


# **Applying styles and colors**


 Here we will explore the canvas options we have at our disposal to make our drawings a little more attractive.

 > ## ***Colors***

Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: ***fillStyle*** and ***strokeStyle***.

**fillStyle = color**

Sets the style used when filling shapes.

**strokeStyle = color**

Sets the style for shapes' outlines.

color is a string representing a CSS <**color**>, a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000).

The valid strings you can enter should, according to the specification, be CSS <**color**> values.

> ## ***Transparency***

In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

globalAlpha = transparencyValue
Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default.
The globalAlpha property can be useful if you want to draw a lot of shapes on the canvas with similar transparency, but otherwise it's generally more useful to set the transparency on individual shapes when setting their colors.

Because the strokeStyle and fillStyle properties accept CSS rgba color values, we can use the following notation to assign a transparent color to them.

___

# **Drawing text**

The canvas rendering context provides two methods to render text:

**fillText(text, x, y [, maxWidth])**

Fills a given text at the given (x,y) position. 
Optionally with a maximum width to draw.

**strokeText(text, x, y [, maxWidth])**

Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.


> ## **Styling text**

There are some more properties which let you adjust the way the text gets displayed on the canvas:

* **font = value**

The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.

* **textAlign = value**

Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

* **textBaseline = value**

Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.

* **direction = value**

Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.

These properties might be familiar to you, if you have worked with CSS before.

