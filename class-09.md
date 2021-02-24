# Forms and JS Events:
**A form is deffirent elements that allow you to collect information from the user, and allow the user to prerform functions online.**
### Types of forms:
* Adding Text:
  * Text input
  * Password input
  * Text area
* Making choice:
  * Radio button
  * Check boxes
  * Dropdown boxes
* Submitting forms:
  * Submit buttons
  * Image buttons
* Upload files

![](https://opentechschool.github.io/python-flask/core/images/form-input.png)

### How forms work?
1. Visitor fills the form and submits it.
2. Data is sent to the web server.
3. The web server processes the request.
4. A response is sent back to the user.

### Form structure:
`<form> , <input>`
type of input
 `:type="text" or "password" , <textarea>,`
select:
 ` radiobutton, checkbox`
 the dropdown list:
 `<select> , <option>value "Radio", "ipod", "computer"`also multiple select.
 ![](https://i.stack.imgur.com/zQ7SO.jpg)
### submit:
`<input>
type="submit"`
The submit button is used to
send a form to the server.
`<input>
type="image"`

### form validation:
Validation helps ensure the
user enters information in a
form that the server will be able
to understand when the form
is submitted.
### date input
`<input>type="date"`
### mail and URL input
`<input>type="email", type="url"`

## Lists, Tables, and forms:
* lists style type:
 * ordered lists
 * unordered lists
* lists style image
* list style position

### Table
* Table properties:
`width` to set the width of the
table,
`padding` to set the space
between the border of each table
cell and its content
`text-transform` to convert the
content of the table headers to
`uppercase`
`letter-spacing`, `font-size`
to add additional styling to the
content of the table headers,
`border-top`, `border-bottom`
to set borders above and below
the table headers
`text-align` to align the writing
to the left of some table cells and
to the right of the others
`background-color` to change
the background color of the
alternating table rows
`:hover` to highlight a table row
when a user's mouse goes over it.
`empty-cells`: show , hide , inherit.
### curser style:
`auto, 
crosshair, 
default, 
pointer, 
move, 
text, 
wait, 
help`.
## Events:
* Scripts use different events to trigger different types of functionality.

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types.jpg)

* How events trigger
JS code :
1. select the element
2. indicate the event
3. state the code needed

* ways to indicate which event for which element:
1. HTML event handlers(No use)
2. Tradetional DOM event handler(`element.onevent=functionName`)
3. DOM level 2 event listener.(`element.addEventListener('event', functionName[, Boolean]);`)



