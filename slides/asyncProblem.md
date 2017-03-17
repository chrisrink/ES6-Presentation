##  The async problem

What we want to do.
```
function getData(cb){
    let results = requestFromServer();
    let values = formatResults(results);
    return calulcatedValues(values);
}

```
But these are async calls, so how do we work around it?
