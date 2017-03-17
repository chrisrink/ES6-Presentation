##  Generators

```
let factory = function*(){
    yield 1;
    yield 2;
    yield 3;
    yield 4;
}

let it = factory();
it.next(); // {value 1, done: false}
it.next(); // {value 2, done: false}
it.next(); // {value 3, done: false}
it.next(); // {value undefined, done: true}

```
Generators are factories for Iterators
