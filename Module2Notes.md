# Module 2: Variables, Data Types, Type Casting, and Comments

### Variables
```var``` , ```let```

-  let prevents us from declaring another variable with the same name
-  Using ```var``` allows you to re-declare a variable, which can potentially lead to errors in the program execution
-  to assign a veriable we use the ```=``` operator
-  ```"use strict";``` forces interpreter to use modern JS standards
-  ```
   let  steps  =  100;
    console.log(steps);  //  ->  100
    steps  =  120;  //  ->  120
    console.log(steps);
    steps  =  steps  +  200;
    console.log(steps);  //  ->  320
   ```
  We can change variables using the method above

### Data Types
- the main types are number and character string

### Constants
- The ```const``` keyword is used to declare containers similar to variables
- this type of container is simultaneously declared and initialized

### Program Blocks
We can separate the code of a program into blocks, see below
```
let  counter;
console.log(counter);  //  ->  undefined
{
         counter  =  1;
         console.log(counter);  //  ->  1
}
counter  =  counter  +  1;
console.log(counter);  //  ->  2
```
The blocks are usually associated with conditional instructions, loops, or functions
We can also nest blocks within blocks (Blockception)
```
let  counter;
console.log(counter);  //  ->  undefined
{
         counter  =  1;
         {
                 console.log(counter);  //  ->  1
         }
}
counter  =  counter  +  1;
console.log(counter);  //  ->  2
```

```let``` and ```const``` when declared inside of a block is local only, outside will be global
```var``` is global almost always, except for when declared inside of a function
