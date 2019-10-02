# Javascript PAINT

HTML5 canvas project for Graphic Computing class

It is a paint-similar application, in which the user can draw, create, move, rotate, transform, delete lines and polygons and polygonals.

## How to use

Drawing:
  - Point: by clicking on the canvas
  - Line: set the start and then the end of the line
  - Polygon: click as many times as you want to draw a polygon. A right click finishes it
  - Polygonal: click as many times as you want to draw a polygonal. A right click finishes it
  
Interacting:
  - Translate: drag the object to wherever you want
  - Rotate: first select the object; click and hold at the center of rotation; holding the left button, move the mouse left or right to rotate counter-clockwise/clockwise
  - Scale: first select the object; scroll with the mouse wheel: up to enlarge, down to reduce
  - Mirror: first select the object; draw a line that will simulate the mirror. The size of the line doesn't matter, just the position
  - Remove: first select the object; right button to remove
  - Convex hull: having at least three points in the canvas (lines have 2 points, polygons and polygonals have n points), clicking in the Convex hull button to generate it around the points

## Demo

![alt text](https://raw.githubusercontent.com/jorgimello/canvas-art/master/demo.png)
