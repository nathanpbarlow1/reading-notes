## Chapter 15: “Layout” (pp.358-404)

**Block level elements** Start on a new line. Examples include: ``<h1> <p> <ul> <li>``
**inline elements** flow in between surrouinding texts. Examples include: ``<img> <b> <i>
**Containing / Parent elements** if one block-level element Sits inside another block level element then the outer box is known as the containing or parent element.

**Controlling the Positions of Elements** Normal flow, Relative Positioning (366), Absolute Positioning (367), Fixed Positioning (368), Floating Elements (pp.70).

**z-index** sometimes referred to as the stacking context.

**float** allows you take an element in normal flow and place it as far to the left or right of the containing element as possible. Anything that sits inside the containing element will flow around the element that is floated.

**Creating multi-column layouts with floats** Many webpages use multiple columns in their design. This is achieved by using a `<div>` element to represent each column. (pp.375)

**Page Sizes** Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens.)

**Fixed width layouts** they do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels. 

**Liquid Layouts** stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.

**CSS Frameworks** aim to make your life easier by providing code for common tasks, such as creating layout griss, styling forms, creating printer-friendly versions of pages and so on. You can include the CSS framework code in your projects rather than writing the CSS from scratch.