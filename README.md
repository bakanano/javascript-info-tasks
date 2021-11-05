# javascript-info-tasks

https://javascript.info/variables
https://javascript.info/operators

# Variables
# Task 1
## Working with variables
1. Declare two variables: admin and name.
2. Assign the value "John" to name.
3. Copy the value from name to admin.
4. Show the value of admin using alert (must output “John”).

# Task 2
## Giving the right name
1. Create a variable with the name of our planet. How would you name such a variable?
2. Create a variable to store the name of a current visitor to a website. How would you name that variable?

# Task 3
## Uppcase const
Examine the following code:

```
const birthday = `18.04.1982`;
const age = someCode(birthday);
```

Here we have a constant birthday date and the age is calculated from birthday with the help of some code (it is not provided for shortness, and because details don’t matter here).

Would it be right to use upper case for birthday? For age? Or even for both?

```
const BIRTHDAY = `18.04.1982`;
const AGE = someCode(BIRTHDAY);
```

-- VARIABLE TASKS END--

# Operators
# Task 1
## The postfix and prefix forms
What are the final values of all variables a, b, c and d after the code below?

```
let a = 1, b = 1;
let c = ++a; // ?
let d = b++; // ?
```

# Task 2
## Assignment result
What are the values of a and x after the code below?

```
let a = 2;
let x = 1 + (a *= 2);
```

# Task 3 
## Type conversions
What are results of these expressions?

```
"" + 1 + 0
"" - 1 + 0
true + false
6 / "3"
"2" * "3"
4 + 5 + "px"
"$" + 4 + 5
"4" - 2
"4px" - 2
"  -9  " + 5
"  -9  " - 5
null + 1
undefined + 1
" \t \n" - 2
```

# Task 4
## Fix the addition
Here’s a code that asks the user for two numbers and shows their sum.

It works incorrectly. The output in the example below is 12 (for default prompt values).

Why? Fix it. The result should be 3.

```
let a = prompt("First number?", 1);
let b = prompt("Second number?", 2);
alert(a + b); // 12
```






