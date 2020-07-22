Chart.js Article
This covers the basics of setting up charts, including setting up the canvas and script, as well as the js syntax.

Basic Usage of Canvas
The canvas element only has two attributes, width and height. Browsers that don't support the canvas element will require a fallback inside of it. The basic context for canvas is 2d, but other contexts are available.

Drawing Shapes with Canvas
Canvas uses coordinate space, with the origin being the top left corner, so all positioning is relative to this point. Canvas only has two primitive shapes, rectangles and paths. Drawing with these methods seems cumbersome but potentially useful. the rest of the methods are simple in theory but appear a little difficult to wrangle. It reminds me of my dad's EDM, a machine that would cut along a pre programmed path.

Applying Styles and Colors
fillStyle and strokeStyle can be used to add color to canvas drawings. Transparency can be added too. The next thing that looks interesting to me is how lining up with the pixel grid is very important for a crisp image.

Drawing Text
Fill and stroke text are the two methods to render text in context with canvas. Text is styling much the same as we have been in css, but in canvas it has a direction and a few other unique features.