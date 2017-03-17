##  For ...of 

```
//ES6
Array.prototype.foo = 1;
let aRay = [1, 2, 3]
aRay[5] = 'bar'
for(let i of aRay){
   console.log(i);
}

//  '0'
//  '1'
//  '2'
// 'undefined';
// 'undefined';
//  '5'
```
-Better