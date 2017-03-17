##  New function syntax

```
//ES5 
function estimateStory(factor){
    return function(factor, estimate = 1){
        return factor * estimate;
    }
}

let chrisEstimate = estimateStory(2*2);
const story = chrisEstimate(3);  
// Outputs 12
```
```
//ES6
chrisEstimate = (factor) => (factor,estimate = 1) => {
    return factor * estimate;
};

```
