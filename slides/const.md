## Immutability

No guarantee of immutability in ES5.
```
var x = 5; 
x= 10;
```
But now we can do

```
const jedi = { isSith: false };
jedi = true; //TypeError 

jedi.isSith=true ; //Shouldn't work. Darkside leads to hate
Object.freeze(jedi);
jedi.isSith=true; //Fails, Powerful you have become
 
```
