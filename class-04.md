# HTML

## Chapter 4: Ch.4 “Links” (pp.74-93)

**Links**
``<a href="https://www.imdb.com">IMDB</a>``

## Linking to other pages on the same site

``<p>
    <ul>
      <li><a href+"index.html">Home</a><li>
      <li><a href+"index.html">Home</a><li>
      <li><a href+"index.html">Home</a><li>
      <li><a href+"index.html">Home</a><li>
    </ul>
  </p>``

## Relative link types by folders (pp.84)

``mail to:``
``target`` if you want a link to open in a new window, you can use the target attribute on the opening <a> tag. The value of this attribute should be _blank">
``<a href+"https://www.imdb.com" target="_blank">``
<!-- Internet Movie Database</a> (opens in new window) -->

## Linking to s aspecifc part on the same page (pp. 87)

## Chapter 15: “Layout” (pp.358-404)

**Block level elements** Start on a new line. Examples include: ``<h1> <p> <ul> <li>``
**inline elements** flow in between surrouinding texts. Examples include: ``<img> <b> <i>
**Containing / Parent elements** if one block-level element Sits inside another block level element then the outer box is known as the containing or parent element.

**Controlling the Positions of Elements** Normal flow, Relative Positioning (366), Absolute Positioning (367), Fixed Positioning (368), Floating Elements (pp.70).

<!-- Note: This layout chapter is BIG. Focus your attention on understanding the core concepts presented on pp.358-364, and look at the code samples on the website that accompanies the textbook. You will have another reading assignment on this chapter, so do not try to digest it all now. -->

## JavaScript

## Chapter 3 “Functions, Methods, and Objects” (pp.86-99 ONLY)

**Functions & Methods** Functions consist of a series of statements that have been grouped together because they perform a specific task. A method is the same as a function, except methods are created inside (and are part of) an object.

**Code Blocks** Code blocks consist of one or more statements contained within curly braces.

**Parameters** Pieces of information that are passed to a function.

**Return value** the answer returned when using a function. 

**Declaring a function** To create a function, you give it a name and then write the statements needed to achieve its task inside the curly braces. This is known as a function declaration. You declare a **function** using the function keyword. You give the function a *name** (sometimes called an identifier) followed by parantheses. The **statements** that perform the task sit in a code block. (they are inside the curly braces.)

**Calling a function** to run the code in the function, you use the function name followed by parantheses.

**Declaring Functions that Need Information**  Sometimes the function needs specific information to performance task. In such cases, when you declare the function you give it parameters. Inside the function, the parameters act like variables.

**Calling Functions that Need Information** When you call a function that has parameters, you specify the values that should use in the parentheses that follow its name. The values are called arguments, and they Can be provided as values or as variables.

Example: getArea (3, 5);
OR
wallWidth = 3;
wallHeight = 5;
getArea(wallWidth, wallHeight);

**Getting a single value out of afunction** (need to review concept again on pp.94)

**Getting Multiple Values out of a Function** (also need to review more and code examples from pp. 95)

**Annonymous Functions & Function Expressions** a **function declaration** creates a function that you can call later in your code. 

**Function Expression** If you put a function where the interpreter would expect to see an expression, then it is treated as an expression, and it is known as a function expression.

**annoymous function** A function with no name.

**immediately invoked function expression** This way of writing a function is used in several different situations. Often functions are used to ensure that the variable names do not conflict with each other (especially if the page uses more than one script).

**Variable scope** The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable scope.

## Article: “6 Reasons for Pair Programming”

2 developers sharing a single workstation to interactively tackle a coding task together.

Typically 2 different roles, the Driver and the Navigator.

Driver types, manages the text editor, version control, etc.

Navigator thinks about the big picture, what comes next, how an algorithm might be converted into code, and also scans for typos or bugs.

## 6 Reasons Why

- Greater efficiency;
- Engaged Collaboration
- Learning from Fellow Students
- Social Skills
- Job Interview Readiness
- Work Environment Readiness
