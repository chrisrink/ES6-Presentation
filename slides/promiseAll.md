##  Promises in Parallel

We can also do parallel operations.
```
function getDinner(){
return Promise.all( 
        callJoe(),
        callAngie(),
        callMom(),
        callDad(),
        "Spicy Bowl"
    )

```
Returns a promise!
