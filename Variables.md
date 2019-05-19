# Variables
Variables are containers of infomation, They are used to store data in memory. This can be retrieved at any time by your program.
Variables can be used to cut down on repetition, and can make your program waaaaaay more readable.

### Variable best practises
- Create your variables with unique descriptive names
- 

Variables are not in themselves **values**, Instead they contain values and represent them with a name.

## Variable keywords
- `var` Creates a new Variable
  ```javascript
  var myName = 'Bobo';
  console.log(myName); // would print Bobo
  ```
- `let` Creates a variable that can be changed
  ```javascript
  let myName = 'Bobo';
  console.log(myName); // Bobo
  //Bobo goes undercover
  myName = 'Nobo';
  console.log(myName); // Nobo
  ```
- `const` Creates a Variable that can not be changed. If you try to reassign it, you will get a `TypeError` returned.

    ```javascript
    const myName = 'Bobo';
    console.log(myname); // Bobo
    ```


You can create `let` or `var` variables with no value. A `const` variable can **not** be initialised without a value.
```javascript
let myName;
console.log(myName); // Would return undefined
myName = 'Bobo'; 
console.log(myName); // Bobo
```

## Maths operators
You can use Maths operators on variables
```javascript
let w = 5;
w = w + 1;
console.log(w); // 6
// There is a better way
let w = 5;
w += 1;
console.log(w); // 6 
```
The `+=` operator adds to the variable then sets the variable to the result.
Other Maths operators can be used in this way `-=` `*=` `/=`

### Increments 

You can increment values stored in Variables using the increment operators
  - `++` increments by 1
  -  `--` increments by -1
  ```javascript
  let w = 1;
  console.log(w); // 1
  w++;
  console.log(w); // 2
  w--;
  console.log(w); // 1
  ```
  ## String concatenation

  You can also concatenate strings in variables.
  ```javascript
  let name = 'Bobo';
  console.log('My name is '+ name + '.'); // My name is Bobo.
  ```

  ## Template Literals
  A template literal allows you to insert variables into a string etc.
  Template Literals are denoted using backticks

  ```javascript
  let name = 'Bobo';
  console.log(`my name is ${name}.` ); // My name is Bobo
  ```

## Typeof Operator
When writing code, it's sometimes handy to be reminded what data type your Variables actually are storing.
```javascript
let nameOf = 'bobo';
let ageOf = 24;
console.log(typeof nameof); // String
console.log(typeof ageOf); // Number
```





