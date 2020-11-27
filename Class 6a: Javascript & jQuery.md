# Reading Notes: Class 6: Javascript & jQuery

## 6a reading notes section notes:

### How HTML, CSS and JavaScript fit together: these three layers form the basis of a popular approach to building webpage  called progressive enhancement.

HTML <html> 	is the content layer
	.html
CSS {css}	 is the presentation layer	
  .css
Javascript ()	is the Behavioral layer	
  .js

JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script. This example adds a greeting into an HTML page. The greeting changes depending on the time of day.

You may see Javascript in the HTML between opening <script> and closing </script> tags (but it is better to put scripts in their own files).

### how To use objects and methods

document.write('Good afternoon!');

The **document** object represents the entire webpage. All web browsers implement this object, and you can use it just by giving its name.

The **write** method of the **document** object allows new contact to be written into the page where the <script> element sits.

document.write('Good afternoon!');

**Member operator** 
	- The **document** object has several methods and properties. They are known as **members** of that OBJECT.
	- You can access the members of an object using a dot between the object name and the member you want to access. It is called A **member operator*
	
**Parameters**
- Whenever a method requires some information in order to work, the data is given inside the parentheses.
- Each piece of information is called a **parameter** of the method. In this case, the write method needs to know what to write into the page.

## JavaScript runs where it is found in HTML

- When the browser comes across a script element, it Stops to load the script and then checks to see if it needs to do anything.

## Summary
### How do I write a script for a web page?
- It is best to keep JavaScript code in its own JavaScript file. JavaScript files or text files, like HTML pages and CSS style sheets, but they have the .js extension. 
- The HTML script element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link> Element can be used to load a CSS file).
- If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the webpage that the browser has created.

## Basic JavaScript Insturctions

### Statements

- A script is a series of instructions that a computer can follow one-bt-one. Each individual instruction or step is known as a **statement**. Statements should end with a semicolon.
	- Each of the lines of code in green is a **statement**. 
	- The pink curly braces indicate the start and end of a code block. 
	- The code in purple determines which code should run. 
- Javascript is case sensitive: 
- Statements are instructions and each one starts on a new line
- Semicolon tells the javascript interpreter when a step is over, indicating that it should move to the next step. 
- Statements can be organized into code blocks by using curly braces. 

### Comments
- You should write **comments** to explain what your code does. 
	/* This script displays a greeting to the user based upon the current time. It is an example from Javascript & jQuery book */

	var today = new Date();			//create a new date object
	var hourNow = today.getHours();		//Find the current hour 
	var greeting;
- Multi-line comment /*, */
- Single line comments //

### Variables
- a Script temporarily stores bits of informnation it needs to do its job in variables. 
- When you write Javascript, you have to tell the interpreter every individual step that you want it to perform. 
- You can compare variables to short-term memory, because once you leave the page, the browser will forget any information it holds. 
- Data stored in a variable can change/vary each time a script runs.
- Before you can use a variable, you need to annouce that you want to use it. This involves creating the variable and giving it a name. Programmer say that you declare the variable. 
- var quantity; (var = variable keyword, quantity =  variable name)
- How to assign variables a value? Once you have a created a variable, you can tell it what info you would like to store for you. 
- Example: quantity = 3 (quantity = variable name, 3 = variable value)

### Data Types

- Numeric Data Type: numbers 0-9. 
- String Data Type: letters a nd other characters.
- Boolean Data Type: can have one of two values: true or false.

### Shorthand for Creating Variables

1) var price = 5;
   var quantity = 14;
   var total = price * quantity;
   
   variables are declared on the same line, then values assigned to each.
  
 2) var price, quantity, total; 
    price = 5;
    quantity = 14;
    total = price * quantity;
    
    Three variables are declared on the same line, then values assigned for each
 
 3) var price =5, quantity = 14;
    var total = price * quantity;
    
    Two variables are delcated and assigned values on the same line. Then one is declared and assigned a value on the next line. 
    
  4) //Write total into the element with id of cost
     var el = document.getElementByID('cost');
     el.textContent = '$' + total;
     
     Here, a variable is used to hold a reference to an element in the HTML page. This allow you to work directly with the element stored in that variable
     
 ### 6 Rules for Naming Variables
 1) The name must begin with a letter, dollar sig, or an underscore. It must not start with a number. 
 2) has The name can contain letters, numbers, dollar sign, or an underscore. Note that you must not use a dash or a period in a variable name.
 3) You cannot use **keywords** or **reserved** words. Keywords are special words that tell the interpreter to do some thing. For example, var is a keyword Used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript.
 4) All variables are case sensitive, so score and Score Would be different very well names, but it is bad practice to create two variables that have the same name using different cases.
 5) User name it describes the kind of information that the variable stores. For example, firstName might be used to store a persons first name, lastName for their last name, and age for their age. 
 6) If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. For example, firstName rate her than firstname (This is referred to as camel case). You can also use an_between each word (you cannot use a dash). 


			
