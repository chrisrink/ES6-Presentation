## Scope Issues

```
if(YesNo){ //Function Scope
    var x = 42; 
}

console.log(x); // 42 - because variable hoisting

if(YesNo){ //Block Scope
    let x = 42; 
}

console.log(x); // Exception: Meaning of Life not found 
 
```