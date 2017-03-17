##  I do not think that word means what you think
### THiS
```
$(document).on("click",function(){
  console.log(this);
}
//window
[1,2,3].forEach(function(item){
  console.log(this)
})
//window

let obk = {
    myfunc: function(){
    
        myCallback(function(){console.log(this)});
   }
}
//window
```