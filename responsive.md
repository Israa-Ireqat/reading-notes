# RegExr:
## The phrase regular expressions, or regexes, is often used to mean the specific, standard textual syntax for representing patterns for matching text.
* A regex processor translates a regular expression in the above syntax into an internal representation that can be executed and matched against a string representing the text being searched in.
* Fields of application range from validation to parsing/replacing strings, passing through translating data to other formats and web scraping.

----
## Anchors — ^ and $:
* `^The        matches any string that starts with The ->`
* `end$        matches a string that ends with end`
* `^The end$   exact string match (starts and ends with The end)`
* `roar        matches any string that has the text roar in it`
## Quantifiers — * + ? and {}:
* `abc*        matches a string that has ab followed by zero or more c`
* `abc+        matches a string that has ab followed by one or more c`
* `abc?        matches a string that has ab followed by zero or one c`
* `abc{2}      matches a string that has ab followed by 2 c`
* `abc{2,}     matches a string that has ab followed by 2 or more c`
* `abc{2,5}    matches a string that has ab followed by 2 up to 5 c`
* `a(bc)*      matches a string that has a followed by zero or more copies of the sequence bc`
* `a(bc){2,5}  matches a string that has a followed by 2 up to 5 copies of the sequence bc`
## OR operator — | or []:
* `a[bc]      same as previous, but without capturing b or c`
## Character classes — \d \w \s and :
* `\d         matches a single character that is a digit` 
* `\w         matches a word character (alphanumeric character plus underscore)`
* `\s         matches a whitespace character (includes tabs and line breaks)`
* `.          matches any character`
* `\D         matches a single non-digit character`
* `\$\d       matches a string that has a $ before one digit`
## Grouping and capturing — ():
* `a(bc)           parentheses create a capturing group with value bc`
* `a(?:bc)*        using ?: we disable the capturing group`
* `a(?<foo>bc)     using ?<foo> we put a name to the group`
## Bracket expressions — []
## Greedy and Lazy match
## Boundaries — \b and \B
## Back-references — \1
## Look-ahead and Look-behind — (?=) and (?<=)

----
# Grid:
###  Grid is the very first CSS module created specifically to solve the layout problems we’ve all been hacking our way around for as long as we’ve been making websites.
* `grid` – generates a block-level grid
* `inline-grid` – generates an inline-level grid
* `<track-size>` – can be a length, a percentage, or a fraction of the free space in the grid (using the fr unit)
* `<line-name>` – an arbitrary name of your choosing
          
             .container {
              grid-template-columns: 40px 50px auto  50px 40px;
             grid-template-rows: 25% 100px auto;`
             }

* grid-template-areas
* grid-template
* column-gap
* row-gap
* grid-column-gap
* grid-row-gap
* justify-content
  * `start` – aligns the grid to be flush with the start edge of the grid container
* `end` – aligns the grid to be flush with the end edge of the grid container
* `center` – aligns the grid in the center of the grid container
* `stretch` – resizes the grid items to allow the grid to fill the full width of the grid container
* `space-around` - places an even amount of space between each grid item, with half-sized spaces on the far ends
* `space-between` – places an even amount of space between each grid item, with no space at the far ends
* `space-evenly` – places an even amount of space between each grid item, including the far ends
# Common Responsive Layouts with CSS Grid:
![](https://mk0bannerflowss888vj.kinstacdn.com/app/uploads/html5responsive.png)
* `grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));`
* `object-fit: cover;`
* `grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;`
* `grid-template-columns: repeat(6, 1fr);`

          column-count: 2;
          column-gap: 20px;
* with no set heights:

        body {
          display: grid;
          grid-template-columns: 200px 1fr 200px;
          grid-template-rows: auto 1fr auto;
          height: 100vh;
          }   

