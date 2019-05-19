# Basic Introduction to JS

## Notation and logging

- `//` Single line comment
- `/* */` Multi line comment
```javascript
/* This is how multi line comments work
console.log('This is commented out);
All the way up to */
console.log('This would not be commented);
```
- `console.log()` writes out the contents of () to the console

## Data Types

- **Number** Any number, including decimals `5` `4.6`
-  **String** Any key on your keyboard, surounded by single or double quotes ( BP to use single quotes ) `'Word'` `"word"` `'123'` `'£$%'`
-   **Boolean** True False, Yes No, On Off, You know this
-   **Null / Undefined** two keywords used to denote absence of value. 
-   **Symbol**
-   **Object** Collection of related data

## Arithmatic Operators

- `+` Add 
- `-` Subtract
- `*` Multiply
- `/` Divide
- `%` Remainder
  ```javascript
  //Simple maths stuff
  console.log(4+5); // 9
  console.log(5-4); // 1
  console.log(5*4); // 20
  console.log(20/4); // 4
  console.log(9%4); // 1
  // add works on strings too
  console.log('Hello'+'World'); //HelloWorld
  ```
  ## Methods and Property Operators

  - The `.` operator acts as a joiner to access mehtods and properties for objects
  ```javscript
  // . Operator in ACTION
  console.log('Hello'.length); // Returns the length of the string 5
  ```
  An obvious method that's been used throughout these notes is the `.log` method.

  ```javascript
  // Other simple Methods on Strings
  console.log('hello'.toUpperCase()); // HELLO
  console.log('   hello  '.trim()); // hello
  console.log('Hello'.startsWith(H)); // true
  ```

  ## Built in Objects
  There are some built in objects within JS 
  which also have their own methods.

  ```javascript
   // For example there is the Math object
  console.log(Math.random()*50);
  // Math.random returns a random number between 0-1. The * 50 then times that result by 50, therefore giving you a random number between 0 - 50
  console.log(Math.floor(Math.random()*50));
  // Math.floor rounds down to the nearest full number. So the above cmd would generate a full number between 0-50
  // Another build in object is Number
  console.log(Number.isInteger(5));
  // This would test if 5 is an integer and return true/false
  ```
  While both properties and Methods are accessed using the `.` operator you can tell them apart by the fact that methods have parentheiss after them and can take arguements 
  - Method ( `Number.isInteger(5);` )
  - A property ( `'Hello'.length` )


