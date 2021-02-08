# ***JavaScript & jQuery***
***********
## **Comparison and Logical operators**:
### ***1. Evaluating conditions***:
*Can compare values even if they are Strings, numbers, or booleans.*

    Equal to ==
    Not equal to !==
    Strict equal to ===
    Strict not equal to !==
    Greater than >
    Greater than or equal >=
    Less than <
    Less than or equal <=

### ***2.Logical Operators:***
*

    And operator &&
    Or operator ||
    Not operator !
    False && anything returns False
    True || anything returns True
## **For and While loops**:

    for (var i=0;i<10;i++)
    {
        document.write (i);
    }
    var i=0 is the initialization
    i<10 is the condition
    i++ is the counter or update

    while (var smth= anything)
    {
        document.write (smth)
    }
*********************
    
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

