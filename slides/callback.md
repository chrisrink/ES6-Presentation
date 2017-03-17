##  Callback Hell

Chaining Async functions sucks 
```
function getData(cb){
    requestFromServer(
        formatResults(
            calculateValues(cb)
        )
    )
}

```
We also need to handle errors at each level.
