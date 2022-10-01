# Python_Part_2
Continuation of Python_Part_1.This python part 2 file contains a learning file for the python programming language with the contents of the material according to what is in read.me


# 13.Operations on List, Set and String
## len()
  Previously we already know that slicing is used for sequences.len() which will calculate the length or number of elements of the List (for String to count the number   of characters).
### Len() on list
### Len() on Set
### len() on string

## min() and max()
  The min() and max() functions are ways to find some minimum and maximum values from a list. MIN() and MAX() cannot be concatenated together between strings and         numbers

## count()
  The count() function is used to find out how many times an object appears in the list.

## Merging and Replication
  In the list it is also possible to have merging(+) and replication (*)

## Range
  The range() function returns a series of numbers with a certain pattern
  • To perform loops (eg for) in accessing list elements, you can use the range() function in python
  • More details on loop operations will be discussed in the Loop and Loop Control module
  The range function can have 1-3 parameters

### Range with 1 parameter n: create a series of numbers starting from 0, as many as n numbers
### Range with 2 parameters n,p: create a series of numbers starting from n, until before p (number p does not follow).
### Range with 3 parameters n, p, q: creates a series of numbers starting from n, until before p (the number p does not follow), with each element having a difference of q.

## In and Not In
Operators in and not in : To find out a value or object is in the list.This function will return a boolean value True or False

## Assign values to multiple variables

## sort()
  sort() method: sort numbers or letters.This sort() method can sort a List.We can also enter the keyword reverse = True in the parameter to make the order reverse.
 str.lower on parameter.This will make the sort method assume all objects are lowercase, without changing the original state of the object


# 14.Operators, Operands and Expressions
  1+2 b+c
  + : Operators
  1,2,or b,c : Variable / operand

## + (add)
## - (Not enough)
Does not apply to strings, will result in an error unsupported operand

## * (Multiplication)
### Returns a string that is repeated a specified number of times

## ** (Rank)
  For the square root, use the power of 0.5

## / (Distribution)
  Returns the result of dividing the first operand by the second operand (float).
## // (Division is divisible by / division)
  Returns the result of dividing the first operand by the second (an integer).

## % (Modulo)
  Returns the remainder for


# 15.Comparison
  Comparison can contain more than two operands
## < (less than)
  Performs a comparison whether the first operand is less than the second operand.Returns a boolean value True or False

## > (greater than)
Performs a comparison whether the first operand is greater than the second operand.Returns a boolean value True or False

## <= (less than or equal to)
Performs a comparison whether the first operand is less than or equal to the second operand. Returns a boolean value True or False

## >= (greater than or equal to)
Performs a comparison whether the first operand is greater than or equal to the second operand. Returns a boolean value True or False

##  == (equal to)
Perform a comparison whether the first operand is the same as the second operand.Returns a boolean value True or False

## != (not equal to)
Performs a comparison whether the first operand is not equal to the second operand.Returns a boolean value True or False


# Boolean Operators
## not (Boolean notes)
If x is True, the function will return False.If x is False, the function will return True

## and (boolean and)
x and y will return False if x is False or the function will return y

## or (boolean or)
x or y. If x is True, the function will return True or the function will return the value of y. In this case, Python also uses short-circuit evaluation because any value of y will not affect the result.


# Short way to write operation
## If you reassign the results of an expression, some of them can be abbreviated
## Usage examples in addition


#Conditional Expressions
## if
  In python, the expression is placed after the if and the decision is determined based on the truth value of the expression. If the expression evaluates to True, the block of statements inside the if statement will be executed. By convention, this block is indented after a colon (:). expression evaluates to False, then the next block (after the IF statement) will be executed

## Else
The Else statement can be combined with the IF Statement, as a way out when the condition / evaluation result is False.Else is optional and singular.

## Elif
Elif stands for else if.Elif is an alternative to nested if.An IF Statement can be written one or more elif statements (optional & not limited)


# 16.For
For is a function that can loop over each type of variable in the form of a collection or sequence. The variable in question can be a list, string or range. If a list or sequence contains an expression, it will be evaluated first. Then the first item in the sequence/list will be deassign as iterating_var variable. After that, the statement block will be executed, continue to the next item, iterate until the entire sequence runs out.

## For Multilevel:
## Writing Letters in Python
## Trying to display letters using the asterisk (*) symbol in python
## Display Letter V
## Showing the letter L
## Else after For
The else function after for is a function that takes precedence over search loops - to provide a way out of the program when the search is not found.


# 17.while
While in Phthon is used to execute statements as long as the given condition is true (True). The condition can be any expression and note that True in Python includes all non-zero values. When the condition becomes False, the program will continue to the line after the statement block. Be careful, later the output will appear continuously without stopping:
## Else after while
## Using Break in While
## Use Continue in While


# 18.Break
The break statement stops the loop then exits, followed by executing the statement after the loop block. If you have a nested loop, break will stop the loop according to the level or loop in which it is. However, if it is placed in a loop with a second depth for example, only the loop stops, not the main loop

# 19.Continue
The continue statement will stop the current iteration
Then continue to the next iteration. Ignore statements that are between continue to the end of the loop block.
## Using List
## Using Range


# 20.Pass
Used when we want a statement or block of statements (statements), but do nothing - continue execution in the order. failure or exception.Pass statement is a Null (empty) operation, nothing happens when it is called
## Before using pass
## After using pass

# 21.List Comprehension (Create a list with inline loops and ifs)
There are times when we need to create a new list from the previous list operation.List comprehensions are a way to generate new lists based on pre-existing lists or iterables
## Search for duplicate letters


# 22.Syntax errors (Syntax Errors)
Error Handling (Error and Exception Handling)
Two types of errors based on their occurrence:
• Syntax errors (syntax errors)
• Exceptions (exceptions)


# 23.Exceptions (exceptions)
Exceptions (exceptions) or often called errors while operating (runtime errors)

* Even if we have written a statement or expression from Python correctly, there is a possibility that an error will occur when the command is executed.
* Errors that occur while the process is in progress are called exceptions and can be fatal if not handled.
* Most exceptions in Python are not handled by the application so the application crashes and then an error message appears.



To find out the various types of default exceptions from Python, you can visit the documentation site from python, namely https://docs.python.org/id/3.8/library/exceptions.html
