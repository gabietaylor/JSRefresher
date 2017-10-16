# JSRefresher
#### JavaScript powers the dynamic behavior on most websites and it's a single threaded language.

# Console 
#### The console is used to record the output of JavaScript programs. The `console.log()` command is used to print, or log, text to the console.

# Data Types
#### Data types are the building blocks of all languages and essential pieces of any program.

* Strings — Any grouping of keyboard characters (letters, spaces, numbers, or symbols) surrounded by single quotes or double quotes.
* Numbers — Any number, including numbers with decimals.
* Either true or false, with no quotations.
* Null — Can only be null. It represents the absence of value.

# Math Operators
#### The value logs in the console.

1. Add `+`
2. Subtract `-`
3. Multiply `*`
4. Divide `/`

# Properties
#### When new data is introduced into a JavaScript program, the browser saves it as an instance of the data type. An instance is an individual case (or object) of a data type.

#### JavaScript will save a new piece of data as a string instance in the computer's memory. A number is stored as an instance of the number data type.

#### A string instance has additional information attached to it. Every string instance has a property called length that stores the number of characters in it. You can retrieve property information by appending the string with a period and the property name.

* The program will print the number of characters in the console.

# Built-In Methods
#### Built-in methods are called by appending an instance with a period, the name of the method, and opening (`(`) and closing (`)`) parentheses.

* `toUpperCase()` -  method returns a string in all capital letters
* `.startsWith()` - will return a boolean of `true` or `false` depending on value

# Libraries
#### Instance methods, by definition, require that you create an instance before you can use them. What if you want to call a method without an instance? That's where JavaScript libraries come in. Libraries contain methods that you can call without creating an instance.

* One such collection contains mathematical methods, aptly named the `Math` library.

# Comments
#### Programs do not evaluate comments when you run them. Good comments are useful for you and other developers, because they describe what the code does.

1. A single line comment will comment out a single line and is denoted with two forward slashes `//` preceding a line of JavaScript code. 
2. A multi-line comment will comment out multiple lines and is denoted with `/*` to begin the comment, and `*/` to end the comment.

# Variables 
### Refer to twoapp.js for further examples
#### Variables are used to write code that is easy to understand and repurpose. Variables allow us to assign data to a word and use the word to reference the data. 

# `const` and `let`
#### Short for constant, is a JavaScript keyword that creates a new variable with a value that cannot change. Constant variables, as their name implies, are constant — you cannot assign them a different value. `let` variables can be reassigned.

# Undefined
#### _Undefined_ is the fifth and final primitive data type. JavaScript assigns the undefined data type to variables that are not assigned a value.

# Math Assignment Operators
####  JavaScript has a collection of built-in _math assignment operators_ that make it easy to calculate a new value and assign it to the same variable without writing the variable twice. 

1. The first three operators (`+=`, `-=`, and `*=`) perform the math operation of the first operator (`+`, `-`, or `*`) using the number on the right, then assign the new value to the variable.
2. The last two operators are the increment (`++`) and decrement (`--`) operators. These operators are responsible for increasing and decreasing a number variable by one, respectively.