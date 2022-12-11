# For Each In Loop

Where the For Loop and For In Loop creates a reference to index of the object in the array, the For Each In Loop creates a variable referencing the actual object.

```javascript
// vms being a array of VMs

for each (vm in vms){
    // Do stuff for each other object here
    System.log(vm.name);
}
```
_Code Example HODHCJ_

If changes are done, it is not reflected in the original array.

```javascript
var fruits = ["Banana", "Apple", "Orange"];

System.log(fruits)
// Output:
// Banana,Apple,Orange

for each (fruit in fruits){
    // Do stuff for each other object here
    fruit = "A slice of " + fruit;
}

System.log(fruits)
// Output:
// Banana,Apple,Orange
```
_Code Example O37QMO_