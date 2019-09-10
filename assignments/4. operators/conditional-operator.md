## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

  ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    * [ ] Sub
    * [ ] Mul
    * [ ] Div
  function calculator(){
    var integer1 = +prompt('enter the first no.');
    var integer2 = +prompt('enter the second no.');
    let operator = prompt("+", "-", "*", "/");
      if(operator=='+'){
        console.log (integer1+integer2)
       }
      else if(operator=='-'){
        if(integer1>=integer2){
           console.log (integer1-integer2)
        }else{
          alert('integer2 is greater than integer1')
        }
     
  }
      else if(operator=='*'){
      console.log (integer1*integer2)
  }
      else if(operator=='/'){
          if(integer1>=integer2){
           console.log (integer1/integer2)
        }else{
          alert('integer2 is greater than integer1')
      }
      }
      else {
        console.log ("invalid input")
      }
  }
    

2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`
```js
var firstName = 'John';
var status = 'single';
// Your code goes here

if (status ==  'single'){
  console.log("john is single")
}else{
  console.log("john is married")
}
```

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
// your code goes here
let first_no = prompt('enter the first integer in number');

let second_no = prompt('enter the second integer in number');

if(first_no > second_no){
  alert("first no is greater then  second no");
}
else{
  alert("second no is greater than first no");
}

```js

// Your code goes here
```



```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js

// Your code goes here
let integer1 = +prompt('enter the first no')
let integer2 = +prompt('enter the second no')
let operator = prompt("enter the operator,+,-,*,/");
if (operator === '+'){
    alert(`addition is ${integer1+integer2}`);
} else if (operator === '-') {
    alert(`substraction is ${integer1-integer2}`);
} else if (operator === '*') {
    alert(`multiplication is ${integer1*integer2}`)
} else if (operator === '/') {
    alert(`multiplication is ${integer1/integer2}`)
}
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here
function statement(value){
  switch(true){
    case value == 1:
    return 'one'
    case value == 2:
    return 'two'
    case value == 3:
    return 'three'
    case value == 4:
    return 'four'
    case value == 5:
    return 'five'
    case value == 6:
    return 'six'
    case value == 7:
    return 'seven'
    case value == 8:
    return 'eight'
    case value == 9:
    return 'nine'
    default:
    return 'invalid input'
  }
  
}
```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// Your code goes here
  function marks() {
    var value= +prompt('enter your marks')
    switch(true){
    case (value >90):
    alert ('AA')
    case (value >80 && value<=90):
    alert ('AB')
    case (value >70 && value<=80):
    alert ('BB')
    case (value >60 && value<=70):
    alert ('BC')
    case (value >50 && value<=60):
    alert ('CC')
    case (value >40 && value<=50):
    alert ('CD')
    case (value >30 && value<=40):
    alert ('DD')
    case (value <=30 ):
    alert ('FF')
    default:
    alert ('invalid input')
    
  }
  }
```
