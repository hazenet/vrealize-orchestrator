# If statement with multiple conditions

**Multiple conditions using logical AND operator**
Here is a If statement with multiple conditions that all needs to be true. Which uses the logical AND operator, written using _&&_

```javascript
var theCharacter = "h";
var theNumber = 7;
if (theCharacter == "h" && theNumber == 7) {
    System.log("Both conditions were true");
}
```
_Code Example T1RGEA_

**Multiple conditions using logical OR operator**
Here is a If statement with multiple conditions where only one of the conditions needs to be true. Which uses the logical OR operator, written using _||_

```javascript
var theCharacter = "h";
var theNumber = 7;
if (theCharacter == "h" || theNumber == 5) {
    // The condition for theCharacter is true, but the condition for theNumber is false
    System.log("At least one of the conditions are true");
}
```
_Code Example L4NJZK_