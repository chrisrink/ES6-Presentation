##  Function Defaults

```
//ES5 
return function(factor, estimate){
    if(!estimate){
        estimate = 1;
    }
    return factor * estimate;
}
//ES6
return function(factor, estimate = 1){
    return factor * estimate;
}
return function(factor, estimate = Math.rand()){
    return factor * estimate;
}
```
We can use functions, functions are lazy
