##  The for ...in problem

```
//ES5
Array.prototype.foo = 1;
var  aRay = [1, 2, 3]
aRay[5] = 'bar'
for(var i in aRay){
    if(aRay.hasOwnProperty(i)){
        console.log(i);
    }
}

//  '0'
//  '1'
//  '2'
//  '5'
```
- Need to check property is not inherited
- We mix empty indexes. (3,4)?