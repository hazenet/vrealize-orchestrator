# JavaScript Basics

## Variables and Objects {#variables-and-objects}

## Comments {#comments}

It's possible to either comment out a single line or a larger block.

```
// Single line comment

/*
Larger block comment, which supports mulitple lines of comments
Comment line 2
Comment line 3
*/
```
_Code Example JDRQWZ_

## Logging {#logging}

## Operators {#operators}

## If statements {#if-statements}

### Simple If statement {#simple-if-statement}

```javascript 
if (3 == 4) {
	System.log("Something is wrong in the universe");
}
```
_Code Example JDRQWZ_


### Single line If statement {#single-line-if-statement}

### If statement with multiple conditions {#if-statement-with-multiple-conditions}

### Else statement {#else-statement}

### If else statement {#if-else-statement}

### Switch statement {#switch-statement}

## Looping {#looping}

### For Loop {#for-loop}

This is the most flexible looping style in Javascript, not the easiest to write or remember.

```javascript
// vms being a array of VMs

for (i = 0; i < vms.length; i++){
    // Do stuff for each object here
    System.log(vms[i].name);
}
```

_Code Example KMXV_

In this example "i" is the variable representing the current index in the array.

The "For" loop has 3 statements:

**Statement 1 - "i = 0" in Code Example KMXV**

Statement 1 is normally used to initialize the iterator variable used in the loop, but it's possible to initialize multiple variables, by seperating them with a comma.

```javascript
// vms being a array of VMs

for (i = 0, prefixVariable = "VM Name: "; i < vms.length; i++){
    // Do stuff for each object here
    System.log(prefixVariable + vms[i].name);
}
```

_Code Example GRCD_

Statement 1 is optional and can be completly omitted, if the iterator variable has been initialized else where in the script.

```javascript
// vms being a array of VMs

var i = 0;
for (; i < vms.length; i++){
    // Do stuff for each object here
    System.log(vms[i].name);
}
```

_Code Example P4ZI_

**Statement 2 - "i &lt; vms.length" in Code Example KMXV**

Statement 2 is normally used to evaluate the condition of the variable used for iteration, and before to decide when to stop iterating.

Statement 2 is also optional, so can like Statement 1 be completely omitted, a "break" statement must be added inside the loop, to avoid a never ending loop.

```javascript
// vms being a array of VMs

var i = 0;
for (;; i++){
    // Do stuff for each object here
    System.log(vms[i].name);
    if (i >= vms.length){
        break;
    }
}
```

_Code Example CDUI_

**Statement 3 - "i++" in Code Example KMXV**

Statement 3 is normally increment the variable used for iteration.

```javascript
// vms being a array of VMs

for (i = 0; i < vms.length; i += 2){
    // Do stuff for each other object here
    System.log(vms[i].name);
}}
```

_Code Example IHH4_

In Code Example IHH4 "i" will be incremented with 2 for every loop.

Statement 3 is also optional, so can like Statement 1 be completely omitted, increments just needs to be done inside the loop.

```javascript
// vms being a array of VMs

var i = 0;
for (;;){
// Do stuff for each other object here
    if (i >= vms.length){
        break;
    }
    i++
}
```

_Code Example HAZB_

### For In Loop {#for-in-loop}

The For In Loop is identical to the functionallity achieved by the For Loop written in Code Example KMXV.

```javascript
// vms being a array of VMs

for (i in vms){
    // Do stuff for each other object here
    System.log(vms[i].name);
}
```

_Code Example LT9G_

So it is a simpler and more readable way of doing a simple loop for each object in a array.

### For Each In Loop {#for-each-in-loop}

Where the For Loop and For In Loop creates a reference to index of the object in the array, the For Each In Loop creates a variable referencing the actual object.

```javascript
// vms being a array of VMs

for each (vm in vms){
    // Do stuff for each other object here
    System.log(vm.name);
}
```

_Code Example TA9D_

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

_Code Example HUS7_

### While Loop {#while-loop}

### Do While Loop {#do-while-loop}

### Break Statement {#break-statement}

### Continue Statement {#continue-statement}

### Label Statement {#label-statement}

## Try {#try}



