##  Get Classy

We finally have OO

```
class Jedi{
    constructor(){
        this.isSith= false; //this gets called when I call "new"
    }

    toString(){
        return `Anger is the path to ${(this.isSith) ? "being Awesome!" : " to the darkside."}`
    }
}

class Sith extends Jedi{
    constructor(){
        super();
       this.isSith = true;
    }
}

```