## Javascript Chapter 3

### Understanding the problem domain is the hardest part of programming

What is the hardest thing about writing code? Many people say Learning a new technology, naming things, testing your code, debugging, fixing bugs, making software maintable.

The big issue is that many problem domains are like a puzzle with a blurry picture or no picture at all.

I’ve spent days trying to implement a feature only to finally go back and talk to a product owner and hash out completely how something should work and why it should work in a particular way, only to go back to my desk and crank out the code in a matter of hours.

It's very difficult to solve a problem before you know the question!

### Chapter 3: Object Literals (pp.100-105)

#### What is an object?

An object group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions take on new names.

In an object: Variables Become Known as Properties.
- If a variable is part of an object, it is called a property. Properties tell us about the object, such as the name of the hotel or the number of rooms that has. Each individual hotel might have a different name and a different number of rooms.

In an object: Functions become known as Methods.
- If a function as part of an object, it is called a method. Methods represent tasks that are associated with the object for example you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms.

Creating an Object: Literal  Notation (pp.102)

Accessing an Object and DOT Notation:
- You can access the properties or methods of an object using.notation. You can also access properties using square brackets.
- To access a property or method of an object you use the name of the object, followed by a period, then the name of the property or method you want to access. This is known as dot notation.
- The period is known as the member operator. The property or method on its right is a member of the object on its left. Here, two variables are created to hold the hotel name and number of vacant rooms.

``var hotelName = hotel.name;``
``var roomFree = hotel.checkAvailability();``

``hotel`` is the object
``name`` and ``checkAvailability`` is the property/method name
`.` is the member operator

### Chapter 5: "Document Object Model" (pp.183-242)

#### Document Object Model

- Specifies how Browsers should create a model of an HTML page and how JavaScript can access and update the contents of a webpage while it is in the browser window.
- The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:

1) Making a model of the HTML page: When the browser loads a webpage, it creates a model of the page in memory. The DOM specifies the way in which the browser should structure this model using DOM tree. The DOM is called an object model because the model (the Dom tree) is made of objects. Each object represents a different part of the page loaded in the browser window.

2) Accessing and Changing the HTML page: The DOM also defines methods and properties to access an update each object in this model, which intern updates what the user sees in the browser. You will hear people call the DOM an application programming interface (API).

#### API

User interfaces let humans interact with programs; APIs let programs (and Scripts) talk to each other. The DOM states what your Scripts can ask the browser about the current page, and how to tell the browser to update what is being shown to the user.

#### DOM Tree Node Types

1) Document Nodes
2) Element Nodes
3) Attribute Nodes
4) Text Nodes

#### Working with the DOM Tree: Accessing the Elements

1) Select an Individual Node: getElementByID(), querySeector()
2) Select Multiple Elements: getElementsByClassName(), getElementsByTagName, querySelectorALL()
3) Traversing Between Element Nodes: parentNode, previousSibling / nextSibling, firstChild / lastChild

#### Working with the DOM Tree: Work with Those Elements

1) Access/Update Text Nodes: nodeValue()
2) Work with HTMl Content: innerHTML, textContent, createElement(), createTextNode(), appendChild(), removeChild()
3) Access or Update Attribute Values: className / id, hasAttribute(), getAttribute, setAttribute, removeAttribute (pp.189)

#### Caching DOM Queries (pp.190-91)

#### Accessing Elements (pp.192-193)

#### NODELISTS: DOM queries that Return more than One Element (pp. 196-197)

getElementsByTagName('h1')
getElementsByTagName ('li')
getElementsByClassName('hot')
querySelectAll('li[``id``]') (pp.197)

#### Selecting an Element from a NodeList (pp.198-199)

#### Looping Through a NodeList

- If you Want to apply the same code numerous elements, looping through a node list is a powerful technique. It involves finding out how many items are in the node list, and then setting a counter to loop through them, one by one. Each time the loop runs, the script checks that the counter is less than the total number of items in the note list. (pp.205)

#### Traversing the DOM (pp. 208)

parentNode
previousSibling
nextSibling
firstChild
lastChild 

#### Review (pp.211-218)

#### Adding or Removing HTML Content (218)

#### Access & Update Text & Markup with innerHTML (pp.220)

#### Adding Elements Using DOM Manipulation (pp. 222)

1) Create the Element: createElement
2) Give it Content: createTextNode()
3) Add it to the DOM: appendChild()

#### Removing Elements via DOM Manipulation 

1) Store the Element to be Removed in a variable
2) Store the Parent of that Element in a Variable
3) Remove the Element from its Containing Element (pp.224)

#### Cross-Site Scripting Attacks (pp. 228)

XSS involes an attacker placing malicious code into a site. Websites often feature content created by many different people. 

#### XSS: Validation & Templates (pp.230)

#### XSS: Escaping Controlling Markup (pp.231)

#### Creating Attributes & Changing their Values (pp.234)




