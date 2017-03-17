## Modules importing

AMD to ES6 Equivalent
```
//sets primary export. similar
import name from path

```
But now we can do:
```
import {f1, f2 } from path

import * from path
require([path],function(es6){
   const main = es6.default 
}

```