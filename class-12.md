# Notes from Read: 12 Chart.js, Canvas
[Home](README.md)

Chart.JS
- app that we use to put serveral types of charts into the page. <br>
- can draw line charts, pie charts, bar charts <br>

artile by Sara Vieira with examples. <br>
https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/

Basic Usage of Canvas <br>
- inacted like an image but with only a height and width. <br>
- defult setting at 300px wide by 150 px high. <br>
- it is rendered the same way we do it with normal DOM Manipulation. <br>
- use the getContext() to see if alternatives need to be used. <br>

Drawing Shapes with canvas <br>
- drawing rectangles. <br>
  - fillRect(x, y, width, height) makes a filled in rectangle. <br>
  - strokeRect(x, y, width, height) makes an outline of a triangle. <br>
  - clearRect(x, y, width, height) clears a rectangle area. <br>
- drawing paths. <br>
  - beginPath() creates new path. <br>
  - path methods methods to set different paths for objects.
  - closePath() adds a straight line to the path, going to the start of the current sub-path. <br>
  - stroke() draws the shape by stroking its outline.
  - fill() draws a solid shape by filling the path's content area. <br>
- Arcs <br>
  - arc(x, y, radius, startAngle, endAngle, counterclockwise) <br>
  - arcTo(x1, y1, x2, y2, radus) <br>
- for list of other shapes https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes

Applying Styles <br>
- colors
 - fillStyle = color: sets the style used when filling shapes. <br>
 - stroke style = color: sets the style for shapes' outlines. <br>
- transparency <br>
  - globalAlpha = transparencyValue: applies the specified transparency value to all future shapes drawn on the canvas. <br>
- line styles <br>
  - lineWidth = value; lineCap = type; lineJoin = type; miterLimit = value; getLineDash(); setLineDash(); setLineDash(); lineDashOffset = value; <br>
- Gradients <br>
  - createLinearGrandiet(x1, y1, x2, y2): creates a linear gradient object with a starting point(x/y 1) and end point (x/y 2) <br>
  - createRadialGradient(x1, y1, r1, x2, y2, r2) <br>
  - createConicGradient(angle, x, y) <br>
- Patterns  <br>
  - repeat, repeat-x, repeat-y, no-repeat  <br>
- Shadows  <br>
  - shadowOffsetX = float; shadowOffsetY = float; shadowBlue = float; shadowColor = color.  <br>

Drawing text
- fillText(text, x, y [, madWidth]) fills a given text at the given x, y position.  <br>
- strokeText(text, x, y [, maxwidth]) strokes a given text at the given xp position.  <br>
styling text
- font = value; textAlign = value; textBaseline = value; direction = value.
