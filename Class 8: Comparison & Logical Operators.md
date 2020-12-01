
## Comparison and logical operators:  Evaluating Conditions (150-151, 156, and 157)

==	Is equal to	This operator  compares two values (numbers, strings, or Booleans) to see if they are the same.
!=	Is NOT equal to	This operator  compares two values (numbers, strings, or Booleans) to see if they are NOT the same.
===	Strict Equal to	This operator compares 2 values to check that both the data type and value are the same.
!==	Strict Not Equal to	This operator compares 2 values to check that both the data type and value are not the same.
Ø 	Greater than	
	
<	Less than	
>=	Greater than or equal to	
<=	Less than or equal to	
&&	Logical AND	This operator tests more than one condition
| |	Logical OR	This operator tests at least one condition
!	Logical NOT	This operator takes a single Boolean value and inverts it…i.e. !(2 < 1) returns TRUE

## Logical Operators

Comparison operators usually returns single values of true or false.

**Logical Operators** allow you to compare the results of more than one comparison operator.

Do expression 1 and expression 2 both evaluate to true?
 - False

Expression 3

((5<2) && (2 >= 3))

Expression 1, Logical Operator, Expression 2 (example above)

Is five less than two?	False
Is two greater than or equal to three?	False

**Short-Circuit Evaluation**: logical expressions are a valuated left to right. If the first condition can provide enough information to get the answer, then there is no need to evaluate the second condition. 

## **for** and **while** loops: 170-173, and 176

### Loops

**Loops** check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. A repeat until the condition returns false. 

There are three common types of loops.
	1) **For**: if you need to run code a specific number of times, use a for loop. It is the most common loop. In a for loop, the condition is usually a counter which is used to tell how many times the loop should run.
	2) **while**: if you do not know how many times the code should run, you can use a while loop. Here are the condition can be some thing other than the counter, and the code will continue to loop for as long as the condition is true.
	3) **Do While**: the do while loop is very similar to the while loop, but has one key difference: It will always run the statements inside the curly braces at least once, even if the condition evaluates to false.

**Loop Counters**

A **for** loop uses a counter as a condition. This instructs the code to run a specified number of times. Here you can see the condition is made up of three statements: initialization, condition, update.
	- **Initialization**: create a variable and set it to zero. This variable is commonly called I, and I access the counter. Example: var I = 0;
	- **condition**: the loop should continue to run until the counter reaches a specified number. Example: I < 10;
	- **update** every time the loop is run the statements in the curly breasts, it adds one to the counter. Example: i++
