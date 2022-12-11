# Switch statement

A "switch" statement is a way to evaluate an expression and run it over multiple "cases" to try and find a match.
It can a bit more compact and easier to structure, than having multiple If Else statements strung together.

```javascript 
switch (vcenter.name) {
    case "vcenter01":
        System.log("This deployment is targeting vCenter01")
        // Do work specific to vCenter01
        break;
    case "vcenter02":
        System.log("This deployment is targeting vCenter02")
        // Do work specific to vCenter01
        break;
    case "vcenter03":
        System.log("This deployment is targeting vCenter03")
        // Do work specific to vCenter01
        break;
    default:
        System.log("This deployment is targeting some other vCenter")
}
```
_Code example 3NS25G_

So in the above example, the first part evaluates the expression (vcenter.name), and temporarily stores that value of that expression.
Then it runs over all the cases and sees if the stored value matches any of the cases.
If no cases are matched, then the "default" section will be executed.
As seen in the example it is recommended to end each case section with a "break" statement, so that the script steps out of the whole "switch" statement.
If the "break" is omitted, then the script will continue and see if the next cases also matches and so on. Which is typically not what is desired.