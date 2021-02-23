# Layout
***CSS treats elements as boxes either block-level or inline elements.***
* **Block-level elements `<h1>,<p>,<ul>`**
* **Inline elements `<img>,<b>,<i>`**
**Parent element is the element containing elements inside.`<div>`**

### **Controling the position of element**
* Normal flow
* Relative positioning
* Absolute positioning
* Position:fixed

### Overlapping elements `z-index`
The z-index is sometimes
referred to as the stacking
context (as if the blocks have
been stacked on top of each
other on a z axis)
### Floating elements `float`
The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.
`body {
width: 750px;
font-family: Arial, Verdana, sans-serif;
color: #665544;}
p {
width: 230px;
float: left;
margin: 5px;
padding: 5px;
background-color: #efefef;}`
### `clear`
* `clear: left`
* `clear: right`
* both
* none
## Fixed widh layout
Advantages
* Pixel values are accurate
at controlling size and
positioning of elements.
*  The designer has far greater
control over the appearance
and position of items on the
page than with liquid layouts.
* You can control the lengths
of lines of text regardless of
the size of the user's window.
* The size of an image will
always remain the same
relative to the rest of the
page.
Disadvantages
* You can end up with big gaps
around the edge of a page.
* If the user's screen is a much
higher resolution than the
designer's screen, the page
can look smaller and text can
be harder to read.
* If a user increases font sizes,
text might not fit into the
allotted spaces.
* The design works best on
devices that have a site or
resolution similar to that of
desktop or laptop computers.
* The page will often take up
more vertical space than a
liquid layout with the same
content.
![](https://internetingishard.netlify.app/fixed-width-vs-fluid-layouts-258df9.e0ad9d98.png)
Liquid layout designs
stretch and contract
as the user increases
or decreases the
size of their browser
window. They tend to
use percentages.
---
Advantages
* Pages expand to fill the entire
browser window so there are
no spaces around the page
on a large screen.
* If the user has a small
window, the page can
contract to fit it without the
user having to scroll to the
side.
* The design is tolerant of
users setting font sizes larger
than the designer intended
(because the page can
stretch)
---
Disadvantages
* If you do not control the
width of sections of the page
then the design can look very
different than you intended,
with unexpected gaps around
certain elements or items
squashed together.
* If the user has a wide
window, lines of text can
become very long, which
makes them harder to read.
* If the user has a very narrow
window, words may be
squashed and you can end up
with few words on each line.
* If a fixed width item (such as
an image) is in a box that is
too small to hold it (because
the user has made the
window smaller) the image
can overflow over the text.
## Layout Grids
Grids set consistent proportions
and spaces between items which
helps to create a professional
looking design. 
---