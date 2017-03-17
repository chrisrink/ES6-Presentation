## Modules exporting

AMD to ES6 Equivalent
```
//sets primary export. similar
define(['jquery'],function($){
    return myFunction
}
export default myFunction
```
But now we can do:
```
export default myFunction;
export otherFunction;
export andAnother;
```