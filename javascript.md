All programming languages contain certain things in them. These things are variables, functions, loops, and other similar things. How they are written and used is usually different for each language but the underlying concepts are generally the same.

Syntax, these are the rules of the language you are using. If your code does not compile, it more than likely is a syntax error.

Never infer logic to a computer or a program. The more literal you are in programming, the easier it is for a computer to understand and compile the program.

## Variables

- To create a variable in javascript you have to start with 3 words, 2 of which you should use for now and one to avoid.

All variables have to start with either const, var, let and then a name. You then assign (using the = sign) it a value.

A variable name is up to you. It does not matter what you call it as long as you are not repeating another variable name. The best practice is to be explicit and literal with the name.

A good name is as follows:
`const studentName = "Ashley"`

A bad name is as follows: `const b = 123`

Always always try to be clear in your code. Clever code is not necessarily easy to understand.

1. `const` stands for constant. This means if you define something with `const`, it will not change.

`const ashley = "ashley"`
ashley is never going to be anything else than what I defined it as.

2. `let` stands for let. This is used if you want to make a variable that you might change the value of later on.

`let ta = "Jaye"`
reassignment
`ta = "Bill"`

You can change a `let` variable as many times as you want. The last time you change it will be what it is going forward.

let ta = "Jaye"
ta = "Randy"
ta = "Rayleigh"
ta = "Gill"

3. `var` is old. Don't use it.

`var` stands for variable.
`var teacher = "Joe"`

You can also reassign it.
`teacher = "Azan"`

You define a variable by using the words `const, let, var`, a name for the variable, and then the = sign (assignment operator).

`const nameOfVariable = whatevervalueyouwant`

## Data types

1. Strings
2. Integers
3. Floats
4. Booleans
5. Arrays
6. Objects

### Strings
Strings are anything in double quotations `""` or single quotations `''` or in javascript `` backticks.

Strings are iterable. It means, you can iterate or go over each individual character of a string. You can also access an individual letter in a string by it's number. Remember, numbers in programming start at 0.
