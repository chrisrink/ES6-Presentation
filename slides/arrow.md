##  Phat Arrow
```

    doThis(callback() => {
        return this.doThat();
    });
    
    //is eqivilent to:
    callback.bind(this);
    
    //or
    $.proxy(callback,function() {
            return this.doThat();
        },this);

```
