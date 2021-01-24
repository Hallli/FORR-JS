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
console.log(`1 + 1 is ${1 + 1}`)
### 2.4
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
```javascript
console.log(`Blessaður ${upplysingar.nafn} þú ert eða ert að verða ${2021-upplysingar.faedingarar} og ert fæddur árið ${upplysingar.faedingarar}`)
```

### 2.5

```javascript
console.log(family.parents.fathers[1].name)
```
### 2.6

```javascript
class User {
  constructor(name, email) {
    this._name = name;
    this._email = email;
  }

  get email() {
    return this._name;
  }

  set email(newEmail) {
    this._email = newEmail;
  }

  get name() {
    return this._name;
  }

  set name(newName) {
    this._name = newName;
  }
}

let user = new User('halli 'halli@bob.com');
console.log(`hallo ${user.name}, netfangið þitt er ${user.email}`);
```
### 2.8

1
2
```javascript
class User {
  constructor(name, email) {
    this.name = name;
    this.email = email;
  }

  setName(newName) {
    this.name = newName;
  }

  setEmail(newEmail) {
    this.email = newEmail;
  }

  getName() {
    return this.name;
  }

  getEmail() {
    return this.email;
  }
}
```
2
```javascript
const user1 = new User('agustuspo', 'agustpolgars@gmail.com')
const user2 = new User('nonnipe', 'nonnipeturs@gmail.com')
const user1obj = {
  name: user1.getName(),
  email: user1.getEmail(),
}
const user2obj = {
  name: user2.getName(),
  email: user2.getEmail(),
}
console.log(user1obj)
console.log(user2obj)
```
