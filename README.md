# Data Type in Python
There are 7 data types that are often used by programmers in Python i.e number such as integer and float, boolean, string, list, tuple, set, and dictionary. all with different usage and built-in that comes with it.

## Number
* Integer or int is a whole number, positive or negative, without decimals, of unlimited length.
* Float or "floating point number" is a number, positive or negative, containing one or more decimals.
* Complex numbers are represented as A+Bi or A+Bj, where A is real part and B is imaginary part.

## String
* String is collection of alphabets, words and characters
* Python has a built-in string class named str
* A whole string is mutable (can be changed), but elements are usually immutable (cannot be changed).

## Boolean
* It's often used for returned value on comparison an expression
* Has a True or a False value

## List
* Lists are a type of ordered data collection and are one of the frequently used variables in Python.
* List elements in Python do not have to have the same data type.
* Lists are declared with square brackets and commas as separating elements.

#### Python List Manipulation
* The del keyword is used to delete an object or an element in an object
* The len() method will return the sum of the total items in an object. on a string, this function will return the number of characters
* The append() method is used to add an item at the end of an object
* The extend() method adds all elements of the iterable to the end of the list.
* The insert() method inserts an element into the object according to the index specified in the parameter
* The remove() method removes the first element whose content is equal to the parameter value
* The pop() method removes the item according to the index in the parameter and returns the deleted value
* The index() method returns the index according to the value written in the parameter
* The count() method returns the number of elements in the object that have the same value in the parameter .
* The sort() method sorts the list items in ascending order by default
* The reverse() method will return list from tail index to head

## Tuple
* Tuple is a type of list whose elements cannot be changed.
* Generally, tuples are used for data that is write-once, and can be executed more quickly.
* Tuples are defined with brackets and elements separated by commas.

## Dictionary
* Dictionaries are not included in the implementation of sequences so they cannot be called with index sequences. 
* For example, in the following example it is tried with index 0, but it produces an error (KeyError) because there is no key (key) 0.

## Set
* A set is a collection which is unordered, unchangeable, and unindexed.
* Sets are used to store multiple items in a single variable and must be unique
* Sets are written with curly brackets {}
* Set items can be of any data type

# I/O Python

## 1. Input
* Output use print() function to output data to standard output device(screen).
* Sometimes use formatting to make print() more attractive by using str.format() on print() parameter

## 2. Output
* Input use input() function to take input from user
* Allow flexibility on programmer with user input

# Python Conditional Expressions

## If
* In Python, an expression follows an if, and the decision is determined based on the truth value of that expression.
* If the expression evaluates to True, then the block of statements within the if statement will be executed.
* As per Conversion, blocks are indented after a colon(:)
* If the expression is evaluated as False, then the next block (after the IF statement) will be executed

## Elif
* Elif is short for else if
* Elif is an alternative to nested if
* An IF statement can be followed by one or more elif statements

## Else
* The Else Statement can be combined with the IF Statement, as a way out when the evaluation condition/result is False.
* Else is optional and singleton

# Python For Loops
* For is a function that can loop over each type of variable in the form of a collection or sequence
* The variable in question can be a list, string, or range
* If a list or sequence contains an expression, it will be evaluated first
* Then the first item in the sequence/list will be assigned as the iterating_var variable
* Afterwards, the block of statements will be executed, moving on to the next item, repeating itself, until the entire sequence is exhausted
