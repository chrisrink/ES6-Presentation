##  The ...Rest operator

```

let [ , , ...y] = [1, 2, 3, 4, 5];
// y = [3, 4, 5];

function sum(...nums){
    console.log(nums);
    return nums.reduce((total,num) => total + num),0)
}

const tots = sum(1,2,3,4,5);
//  LOG: [1,2,3,4,5]
//  tots = 15;


```
