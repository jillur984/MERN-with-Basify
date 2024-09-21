# what is Javascript ?

JavaScript is a scripting programming language used primary for web development. While HTML and CSS handle the structure and styling of the web page (UI), JavaScript allows for dynamic interactions and manipulation of these elements. If we want to interact with the content, attributes, and styles of the web page (like handling user inputs, animations, or dynamically updating data), we use JavaScript.

## what is variable

Variable is like a storebox where we store data. suppose when we store multiple store data but if have no name or someting unique i mean looks like same that time we confuse about this and we are not able to find our desire data. If i have variable i can given a unique name that is very helpfull for me find data. When need i call that and retrive also all time.

Example i given below:


 const name="Jillur"
 const age="26"
 Country="Bangladesh"

 here name,age,country all are variable. Sometimes we need to store multiple variable that time we can use Array. If need more that time can use Object. In array we can store all String but in Object we are store multiple type key,value,pair.


 ## data types in JS:

 There are 2 types data types:
 1. Primitive Data Type-String, Number, Boolean, Undefined, Null, Symbol, BigInt
 2. Non Primitive Data Types-Object (which includes Arrays, Functions, Dates, etc.)

 I explain in a word this. Primitive Data are immutable and this all type of data store in stack (is a Data Structure name) separately

 But Non Primitive we are keep by reference in heap Memory and all are mutable. 


## Start Day-2 here

# Arithmatic Operator

In JavaScript, arithmetic operators are used to perform basic mathematical operations on numbers. Here are the common arithmetic operators.

example-
let sum = 5 + 3;  // Result: 8

## Assignment Operator

In JavaScript, assignment operators are used to assign values to variables. The most basic assignment operator is the equal sign (=), but there are several others that perform operations and then assign the result to the variable.

Example-const x = 10;  // x is assigned the value 10

## Comparision Operator

There are many comparison operator in js

1.== this use for equal two value
e.g.  let x==y .here compare x is equal y or not ??

2.=== strickly Equal check

let c = '5'; // string
let d = 5;   // number

console.log(c === d); // false because value same but type is not same

3.Greatter than,Less than and less than equal and greeter than equal is very simple stuff.

here are some comparision operator example-

console.log(5 == '5');      // true
console.log(5 === '5');     // false
console.log(5 != '5');      // false
console.log(5 !== '5');     // true
console.log(10 > 5);        // true
console.log(10 >= 10);      // true
console.log(5 < 10);        // true
console.log(5 <= 5);        // true

## Logical opeator

in Programming we most use and,or not.

# And Operator
The AND operator returns true if both operands are true; otherwise, it returns false.
let a = true;
let b = false;

console.log(a && b); // false (both must be true)
console.log(a && true); // true (first operand is true)

# Or Operator

The OR operator returns true if at least one of the operands is true; it returns false only if both operands are false.

let c = false;
let d = true;

console.log(c || d); // true (at least one operand is true)
console.log(false || false); // false (both operands are false)

# Not Opearator

The NOT operator negates the boolean value of the operand. It returns true if the operand is false and false if the operand is true.

let e = true;

console.log(!e); // false (negation of true)
console.log(!false); // true (negation of false)


# conditional ternary operator

The ternary operator in JavaScript is a shorthand for if...else statements. It has the following syntax:

let age = 18;
let canVote = (age >= 18) ? "Yes, can vote" : "No, too young"; here ? is ternary operator and : also write for else

console.log(canVote); // "Yes, can vote"

# Operator precednce

In JavaScript, operator precedence determines the order in which operations are evaluated when an expression has more than one operator. Operators with higher precedence are evaluated before operators with lower precedence

# Operator Precedence Table


Which Operator need to work first priyority is called operator precedence

in JavaScript, operator precedence dictates the order of evaluation in expressions. Parentheses () have the highest precedence, followed by postfix increment and decrement operators ++ and --. Unary operators (++, --, +, -, ~, !) are next, followed by exponentiation **. Multiplication, division, and modulus (*, /, %) are evaluated from left to right, followed by addition and subtraction (+, -). Bitwise shift operators (<<, >>, >>>) come next, then comparison operators (<, <=, >, >=) and equality operators (==, !=, ===, !==). Bitwise operations include AND &, XOR ^, and OR |. Logical AND && and OR || evaluate boolean expressions, while the ternary operator ?: offers conditional evaluations. Assignment operators = and compound assignments (+=, -=, *=, /=, %=) assign values, and the comma operator , evaluates expressions from left to right but returns the last value. Parentheses can clarify the desired order of operations.