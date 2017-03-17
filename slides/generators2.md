##  Generators are iterator and iterable

```
function zeroOneTwo(){
   return [0,1,2]
}
//or
function zeroOneTwo(){
    yield 1;
    yield 2;
    yield 3
}
```
Both output the same
```
var aRay = zeroOneTwo();
for(var i of aRay){
    console.log(i);
} 
// '1', '2', '3'

```
