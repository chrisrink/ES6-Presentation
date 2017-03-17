##  Iterator

```
let it = [1, 2, 3][Symbol.interator]();
it.next(); // {value 1, done: false}
it.next(); // {value 2, done: false}
it.next(); // {value 3, done: false}
it.next(); // {value undefined, done: true}
```
