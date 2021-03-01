# Docs for the HTML `<canvas>` Element & Chart.js
## *Creating animated chart in chart.js*
![](https://miro.medium.com/max/3648/1*rEZJ5Y_BiurUpvWZWRJx9w.png)
Charts are the best way to view data insteadof tables. CHART.JS is a tool to draw charts .
To download it a script must be written in a nwe  HTML page.
### `<!DOCTYPE html>`
### `<html lang="en">`
### `<head>`
 ### `<meta charset="utf-8" />`
 ### ` <title>Chart.js demo</title>`

### `<script src='Chart.min.js'></script>`
### ` </head>`
### `<body>`
### `</body>`
### `</html>`

then add the chart in the body of HTML  using `<canvas>`element
* line chart (chart().line)
* pie chart (chart().pie)
* bar chart (chart().bar)
### **Id is required in `<canvas>`**

## Drawing rectangles:
![](https://i.imgur.com/IPis8uw.png)
* `fillRect(x, y, width, height)`draws  filled rectangle.
* `strokeRect(x, y, width, height)` draws rectangle outlines.
* `clearRect(x, y, width, height)` make a transparent rectangle.
## Many shapes can be drawn like arcs lines , and compinations.
![](https://i0.wp.com/www.cssscript.com/wp-content/uploads/2018/07/Versatile-Interactive-SVG-Chart-Library-apexcharts.js.png?fit=833%2C578&ssl=1)
## Colors:
Colors also can be filled or outlines.`globalAlpha = transparencyValue` this command is used for a transparent color.
## line styls:
* `lineWidth = value`
* `lineCap = type`
* `lineJoin = type`
* `miterLimit = value`
* `getLineDash()`
* `setLineDash(segments)`
* `lineDashOffset = value`
## Texts also can be filled or outlined and styled.


