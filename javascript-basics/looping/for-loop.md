# For Loop

This is the most flexible looping style in Javascript, but not the easiest to write or remember.

```javascript
// vms being a array of VMs

for (i = 0; i < vms.length; i++){
    // Do stuff for each object here
    System.log(vms[i].name);
}
```
_Code Example LB5DB2_

In this example "i" is the variable representing the current index in the array.

The "For" loop has 3 statements:

**Statement 1 - "i = 0" in Code Example LB5DB2**

Statement 1 is normally used to initialize the iterator variable used in the loop, but it's possible to initialize multiple variables, by seperating them with a comma.

```javascript
// vms being a array of VMs

for (i = 0, prefixVariable = "VM Name: "; i < vms.length; i++){
    // Do stuff for each object here
    System.log(prefixVariable + vms[i].name);
}
```
_Code Example BJ1ULP_

Statement 1 is optional and can be completly omitted, if the iterator variable has been initialized else where in the script.

```javascript
// vms being a array of VMs

var i = 0;
for (; i < vms.length; i++){
    // Do stuff for each object here
    System.log(vms[i].name);
}
```
_Code Example K1QV3R_

**Statement 2 - "i &lt; vms.length" in Code Example LB5DB2**

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
_Code Example E0KL18_

**Statement 3 - "i++" in Code Example LB5DB2**

Statement 3 is normally increment the variable used for iteration.

```javascript
// vms being a array of VMs

for (i = 0; i < vms.length; i += 2){
    // Do stuff for each other object here
    System.log(vms[i].name);
}}
```
_Code Example 6HHJZE_

In Code Example 6HHJZE "i" will be incremented with 2 for every loop.

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
_Code Example 6CBBTH_