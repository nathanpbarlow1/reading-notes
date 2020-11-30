## Intro + Scripts: pages 1-24
	- Program rules: a gallery script could check which image a user clociked on and display a larger version of that image
	- React to events: you can specify that a script should run when a specific event has occurred. For example: a button is pressed, a link is clicked, an interval of time has passed, etc. 
	- Slideshows: slide shows can display a number of different images within the same space on a given page. They can play automatically as a sequence, or users can click through the slides manually. They allow more contact to be displayed within a limited amount of space..
		○ React: script triggered when the page loads.
		○ Access: get each side from the slideshow
		○ Modify: only show the first slide (hide others)
		○  Program: set a timer when does show next slide..
		○ Modify: change which slide as shown.
	- Forms: validating forms is important when information is supplied by users. JavaScript lets you alert the user if mistakes have been made. They can also perform sophisticated calculations based on any data entered and revealed the results to the user.
	- HTML & CSS Refresher: 
		○ .fruit {color: pink;}
			§ .fruit (selector)
			§ {color: (property name)
			§ Pink (property value)
			
### what is the script and how do I create one?

The script is a series of instructions that a computer can follow to achieve a goal. You could compare Scripps to any of the following: recipes, handbooks, manuals.

Scripts are made up of instructions a computer can follow step-by-step. A browser may use different parts of the script depending on how the user interacts with the webpage. Scripts can run different sections of the code in response to the situation around them.

To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.

Start with the big picture of what you want to achieve, and break that down into smaller steps.
	1) Defined the goal
	2) Design the script
	3) Code each step


## Expressions + Operators: 74-79

**Expressions**: an expression evaluates into (results and) a single value. Broadly speaking there are two types of expressions.
	1) Expressions that just assign a value to a variable
		a. In order for a variable to be useful, it needs to be given a value. As you have seen, this is done using the assignment operator (the = sign)
		b. var color = 'beige';
		c. The value of color is now beige
		
	2) Expressions that use two or more values to return a single value
		a. Var area = 3 * 2;
		b. The value of area is now 6

**Operators**: expressions rely on things called **operators**; they allow programmers to create a single value from one or more values.
	- **assignment operators**: assign a value to a variable (color = 'beige';
	- **arithmetic operators** performs basic math (area = 3 *2;)
	- **string operators** combine two strings (greeting = 'Hi ' +Molly';)
	- **comparison operators (compare 2 values and return true or flase): buy = (5>3) && (2 < 4); ---the value of buy is now true

**Mixing Numbers and Strings Together**
	- When you place quotes around a number , it is a string, not a numeric data type, and you cannot perform additional operations on strings.
		○ Var cost1 = '7';
		○ Var cost2 = '9';
		○ Var total = cost1 + cost2; 
	- You would end up with a string saying '79'
	
		

## Functions: 88-94

**what is a function?**

Functions like your group as series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function rather than repeating the same set of statements.

If you were going to ask the function to performance task later, you need to give your functioning name. That name should describe the task it is performing. When you ask it to performance task, it is known as **calling** the function.

When you write a function and you expected to provide you with an answer, the response is known as a **return value**

**declaring a function**

To create a function, you give it a name and then write the statements needed to achieve its task inside the curly braces. This is known as a function declaration.

You declare a function using the ** function** keyword.

You give the function a name followed by parentheses.

The **statements** that perform the task set an a code block. They are inside curly braces.

Function sayHello() {
	document.write('Hello!');
