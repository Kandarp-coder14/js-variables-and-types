# Expression vs Statement

A program, often referred to as source code, is a set of instructions to tell the computer what tasks to perform. The rules for valid format and combinations of instructions is called a computer language, sometimes referred to as its `syntax`, much the same as English tells you how to spell words and how to create valid sentences using words and punctuation.

## Statements
In a computer language, a group of words, numbers, and operators that performs a specific task is a statement. In JavaScript, a statement might look as follows:
```js
var a = 21;

var b = 30;

a = b * 4;
```

The character `a` and `b` are variables. `Variables` are store of value (a box that stores value like number 21). The `=` and `*` characters are operators, they perform specific operation on values and variables.

The statement `a = b * 4;` tells the computer, roughly, to get the current value stored in the variable `b`, multiply that value by `2`, then store the result back into another variable we call `a`.

Programs are just collections of many such statements, which together describe all the steps that it takes to perform your program's purpose.

## Expressions

Expressions are values. Statements are made up of one or more expressions. An expression is any reference to a variable or value, or a set of variable(s) and value(s) combined with operators. For example:
```js
a = b * 2;
```

This above statement has four expressions in it:

  *. 2 is a literal value expression
  *. b is a variable expression, which means to retrieve its current value
  *. b * 2 is an arithmetic expression, which means to do the multiplication
  *. a = b * 2 is an assignment expression, which means to assign the result of the b * 2 expression to the variable a (more on assignments later)



For example:

```js
var num = 45;
num = var a = 21;
```

45 is a value in the above statement. Value is an expression. Is the line 41 valid? It's not because you can't put statement in place of expression. You can only put a value after the `=` sign when you are defining the variable.


To understand the difference between them you can watch this video.
[Expressions vs. Statements](https://www.youtube.com/watch?v=WVyCrI1cHi8)