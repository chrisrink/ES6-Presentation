##  The ...Spread operator

```
//These are the same
Object.assign === $.extend === _.extend

They can be used to clone and shallow merge
let merged = Object.assign({},{a:1},{a:2, b:3});
//merged === { a:2, b:3 }

But now we can do:

merged = {
    ...a,
    ...b
}

This also works on functions
function f(x, y, z) {
  return x + y + z;
}
// Pass each elem of array as argument
let aRay = [1,2,3]
f(...aRay) == 6

```
