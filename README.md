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
let oddNumbers= numbers.map((value) =>{
  return value % 2 === 0 ? value * 0 :value
})

for( var i = 0; i < oddNumbers.length; i++){ 
  if ( oddNumbers[i] === 0) { 
    oddNumbers.splice(i,1); 
    i--; 
  }
}
console.log(oddNumbers);
```

### 2
1
```javascript
const upplysingar = {
  nafn: 'Halli',
  faedingarar: 2003,
  email: ['haraldur.sigfus@gmail.com', 'hsm@gmail.com', 'halli@gmail.com']
};

//upplysingar.nafn
//upplysingar.faedingarar
//upplysingar.email
```
2
### 2.5

```javascript
console.log(family.parents.fathers[1].name)
```
