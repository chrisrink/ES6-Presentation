##  Async-Await


```
async function getData(cb){
     let results = await requestFromServer();
     let values = await formatResults(results);
     return calulcatedValues(values);
}

```
WHAT!!!! This is what we wanted at the beginning. backed by promises.
