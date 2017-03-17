##  Generators*


```
function* getData(cb){
     let results = yield requestFromServer();
     let values = yield formatResults(results);
     yield calulcatedValues(values);
}

```
Better - Getting closer but I need some middleware to run this.
