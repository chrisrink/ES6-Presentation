##  The Promised land


```
function getData(cb){
    return requestFromServer
        .then(function(res){
            return formatResults(res);
        })
        .then(function(values){
            return calulateValues(values)
        })
    )
}

```
Better - Promise changes allow use to bubble errors up.
