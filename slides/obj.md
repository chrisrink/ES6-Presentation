## Object Upgrades


Now you can do:

```
const hasLightSaber = true;
const property = 'hasBeard';
const master = {
 __proto__: jedi,  //Sets the prototype that you extend from.
 [property]: true,  //computed keys
 hasLightSaber, // shorthand for adding key using function key.
 forcePush(){}  // functions too!
}

master.isSith; //false
master.hasBeard; //true
master.hasLightsaber; //true
master.forcePush() //KaPOWWWW!

```