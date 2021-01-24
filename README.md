# FORR3JS05DU
jejje verkefni 2

### 2.2
1
```javascript
const add  = (a, b) => a + b;
  const sum = add(1,2);
  console.log(sum);
```
2
```javascript
function add(a,b){
    return a + b;
}
const sum = add(1,2);
console.log(sum);
```

### 2.3
1

```javascript
let numbers = [1, 2, 3, 4, 5];
var oddNumbers=[]
for (let teljari = 0; teljari < numbers.length;teljari++) {
    if (numbers[teljari] % 2)
    oddNumbers.push(numbers[teljari]);
}

console.log(oddNumbers);
```

2
```javascript
let numbers = [1, 2, 3, 4, 5];
let nyttnumer= numbers.map((value) =>{
  return value % 2 === 0 ? value * 0 :value
})

for( var i = 0; i < nyttnumer.length; i++){ 
  if ( nyttnumer[i] === 0) { 
    nyttnumer.splice(i,1); 
    i--; 
  }
}
console.log(nyttnumer);
```
