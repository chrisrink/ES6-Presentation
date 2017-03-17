##  Function Declarations
```

let log = statement => console.log(statement);

let namedLog = (stmt,name) => console.log(`$(name) said: $(stmt)`);

let complexLog = (statement) => {
    if(statement.includes("error")){
        console.error(statement);
    }else{
        console.log(statement);
    }
 
}


```
