# **HTML lists**
---
## **There are three types of lists :**
* **Unordered list**\<ol><li>
* **Ordered list**\<ul><li>
* **Defenition list** \(A set of terms with their defenitions)
  * \<dl>
  * \<dt> **The term to be defiend.**
  * \<dd> **The definition.**

 ![](https://clarkwp.files.wordpress.com/2013/10/lists_and_nested_lists_in_wordpress.png?w=311)

 # **HTML boxes**
 ---
 ## **Boxes dimensions :**
 **Dimensions of the box can be adjusted by using CSS**
 * Width and Hight 
 ![](https://daqxzxzy8xq3u.cloudfront.net/wp-content/uploads/2019/05/20122804/display-block-example-css-code-2.png)

 ## also it is a vailable to limit the dimensions.
   
    div {
      max-width: 500px;
      height: 100px;
      background-color:powderblue;
     }

### **Border, Margin, and padding**
 
` p.example1 {
            border:1px solid;
            border-bottom-color:#009900; /* Green */
            border-top-color:#FF0000;    /* Red */
            border-left-color:#330000;   /* Black */
            border-right-color:#0000CC;  /* Blue */
         }  `

#### *Padding is used to specify the space needed between the content and the border of an element*

# **JS Arrays, Desicions and loops.**
---
#### **Array is a type of variables that can store more than one value. Values inside the array can be in any date type of JS or more than one data type in the same array.**
Example:
`
let colors = ['red', 'green', 'blue'];
`
##### Arrays numbering of elements sterts with 0.
`
let fruits = ["Figs", "Banana", "Mango", "Orange", "Papaya"];
fruits=[0] represents the element  (Figs)
fruits=[1] represents the element  (Banana)
fruits=[2] represents the element  (Mango)
`
#### The value of an element in the array can be changed.
`
let colors = ['red', 'green', 'blue'];
let colors[2]=Black;
`

---
---
### **If else statement**
![](https://th.bing.com/th/id/R72ed19cea74119a275e57a5a4bf29b0c?rik=4QPViB%2fl1Lv6Qw&riu=http%3a%2f%2fwww.kirupa.com%2fhtml5%2fimages%2fif_else_72.png&ehk=Ij6ACLCTJg%2fhnl9txNThMOZ0%2blFyGb2alV8NXp6tRuU%3d&risl=&pid=ImgRaw)

### **Switch elements:**
***The switch case is a decision-making statement in JavaScript which is used to execute a specific block of code against an expression.***

     swinum = 3;
 
     switch(swinum){
 
     case 1:
 
     alert ("Case 1 is true!");
 
     break;
     case 2:
     alert ("Case 2 is true!");
     break;
     case 3:
     alert ("Case 3 is true!");
     break;
     default:
    alert ("None of the case is true!");
    break;
    } 


### **Loops**
## **For and While loops**:

    for (var i=0;i<10;i++)
    {
        document.write (i);
    }
    var i=0 is the initialization
    i<10 is the condition
    i++ is the counter or update

---
  
    while (var smth= anything)
    {
        document.write (smthth)
    }



---


**Example**:

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

