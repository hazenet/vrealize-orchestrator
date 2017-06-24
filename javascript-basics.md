# JavaScript Basics

## Variables and Objects {#variables-and-objects}

## Comments {#comments}

It's possible to either comment out a single line or a larger block.

```js
// Single line comment

/*
Larger block comment
*/
```

## Logging {#logging}

## Operators {#operators}

## If statements {#if-statements}

## Looping {#looping}

### For Loop {#for-loop}

This is the most flexible looping style in Javascript, not the easiest to write or remember.

```js
for (i = 0; i < 10; i++){
    // do stuff
}
```

_Code Example KMXV_

In this example "i" is the variable representing the current iteration.

The "For" loop has 3 statements:

**Statement 1 - "i = 0" in Code Example KMXV**

Statement 1 is normally used to initialize the iterator variable used in the loop, but it's possible to initialize multiple variables, by seperating them with a comma.

```js
for (i = 0, otherVariable = "something"; i < 10; i++){
    // do stuff
}
```

_Code Example GRCD_

Statement 1 is optional and can be completly omitted, if the iterator variable has been initialized else where in the script.

```js
var i = 0;
for (; i < 10; i++){
    // do stuff
}
```

_Code Example P4ZI_

**Statement 2 - "i &lt; 10" in Code Example KMXV**

Statement 2 is normally used to evaluate the condition of the variable used for iteration, and before to decide when to stop iterating.

Statement 2 is also optional, so can like Statement 1 be completely omitted, a "break" statement must be added inside the loop, to avoid a never ending loop.

```js
var i = 0;
for (;; i++){
    // do stuff
    if (i >= 10){
        break;
    }
}
```

_Code Example CDUI_

**Statement 3 - "i++" in Code Example KMXV**

Statement 3 is normally increment the variable used for iteration.

```js
for (i = 0; i < 10; i += 2){
    // do stuff
}}
```

_Code Example IHH4_

In Code Example IHH4 "i" will be incremented with 2 for every loop.

Statement 3 is also optional, so can like Statement 1 be completely omitted, increments just needs to be done inside the loop.

```js
var i = 0;
for (;;){
    // do stuff
    if (i >= 10){
        break;
    }
    i++
}
```

_Code Example HAZB_

### For In Loop {#for-in-loop}

### For Each In Loop {#for-each-in-loop}

### While Loop {#while-loop}

### Do While Loop {#do-while-loop}

### Break Statement {#break-statement}

### Continue Statement {#continue-statement}

## Try {#try}



