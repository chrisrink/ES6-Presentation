##  Array

```
Array.from(gen(6));
// let aRay = Array [0, 1, 2, 3, 4, 5, 6]

let aRay = Array.from(gen(6), function(x){ return x*x});
//[0 ,1, 4, 9, 16, 25, 36]

aRay.keys();
// [0,1,2,3,4,5,6]

aRay.entries();
//[[0,0],[1,1],[2,4], [3,9] ....]
```