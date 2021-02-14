# **HTML Text**
***Markup tags are added to the content of the web pages, the allow the browser to show appropriate structure of the page>***

*******
## ***Markup types***
* #### **Structural markup (to describe headings and paragraphs):**
   * Headings **\<h1>,<h2>,..,\<h6>**
   * Paragraphs **\<p>**
   each paragraph element is shown in a new line.
   * **Bold** **\<b>**
   * *Italic* **\<i>**
   * Suprescript **\<sup>** it is used in mathmatical eqauations such powers of the numbers.
   * Subscript **\<sub>** it is used to show foot notes such as numbers under the chemical formulas.
   * Line breackes **\<br />**
   it writes the next paragraph on a new line.
   * Horizontal rules **\<hr />** it draws a horizontal line between the paragraphs.

* #### **Semantic markup (Provides extra information):** 
    * Strong **\<strong>** it is shown in bold that are  in strong importance information.
    * *Emphasis* **\<em>** .
    * "Quotations"  **\<q>**
    *  Abbriviations **\<abbr>**
    * Acronyme **\<acronyme>** it shows the text inside a box.
    * *Citation* **\<cite>** used for books names, newsletters, reasearch books.
    * Defenitions **\<dfn>** may appears in italic.
    * Author details **\<adress>** used to contain contact details.
    * **\<del>** Makes a line through the text.
    * **\<ins>** Makes the text underlined.
    ****
     
   ## ***CSS***
    ***CSS associates style rules with HTML elements and affect hoe they are displayed.***
    ### *Style example in CSS*
    * Boxes width,hight,colors and position.
    * Text size, type, and color.
    * Specific lists, tables and forms.
    #### **Using external CSS** 
    **\<link rel="stylesheet" href="design.css">**
    #### **Using internal CSS.**
    **\<style>
            h1 {
               color: blue; 
               }
             \</style>**

## **CSS selectors**
* Type selector
* Class selector
* Global selector
* ID selector
and other selectors.
![](https://i.pinimg.com/originals/bc/97/96/bc97965579512f8a6d2303934f599c65.png)

# **Java Script**
## *Statements in JS*:
* A statement is the step or the individual instruction that the computer follows and it ends with a semi colon.
* JS is case sensetive.
* You can write a comment in JS by typing a back slash with star for the single-line comment and by typing double-back slash for the multi-line comment.
* A variable is a script that its value can be changed.
* There aer three data types in JS:
  * **Number**
  * **String** for letters
  * **Boolean** True or False
 * Quotes is written by typing a back slash before the quote.
 * **Array**: it is a special type of variables that stores more than one value.
 ![](https://miro.medium.com/max/7208/1*FTeGAr2QeoFgYXWNQ2leuA.png)

## **Condetional statements**
![](https://miro.medium.com/max/1200/0*ZNBR1fzvqYEqtM5M)

## Comparison operators:

    Equal to ==
    Not equal to !==
    Strict equal to ===
    Strict not equal to !==
    Greater than >
    Greater than or equal >=
    Less than <
    Less than or equal <=
### Logical

    And operator &&
    Or operator ||
    Not operator !
    False && anything returns False
    True || anything returns True

   ## **Example**:

    var order =prompt ("What Do you  prefer a Hotel or a Motel?");
    while (order !== "Hotel" && order !== "Motel") 
    {
        order= prompt ("What Do you prefer a Hotel or Motel?")
        }
    


    for (var i =0 ;i<numOfbeds ;i++)
    {
    result=result+choice
    }
    document.write (result);
