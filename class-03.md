# HTML

## Chapter 3: "Lists" (pp. 62-73)

## There are 3 different types of lists

**Ordered Lists**: lists where each item in the list is numbered (recipes)
**Unordered lists**: lists that begin with a bullet point (rather than characters that indicate order)
**Definition lists**: made up of a set of terms along with the definitions for each of those terms.

## Chapter 13: "Boxes" (300-329)

The most popular ways to specify the size of a box are to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size.

When you use percentages, the size of the box is relative to the size of the browser window or, if the box is encased within another box, it is a percentage of the size of the containing box.

When you use ems, the size of the box is based on the size of text within it. Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens.

**min-width** this property specifies the smallest size a box can be displayed at when the browser window is narrow.

**max-width** indicates the maximum width a box can stretch to when the browser window is wide.

**hidden** this property simply hides any extra content that does not fit in the box.

**scroll* this property adds a scrollbar to the box so that users can scroll to see the missing content.

**overflow** this property is handy because some browsers allow users to adjust the size of the text to appear as large or as small as they want.

Every box has 3 available properties that can be adjusted to control its appearance

**Border** Every box has a border (even if it is not visible or is specified to be 0 pixels wide)

**Margin** Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the border of two adjacent boxes.

**Padding** this is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

**border-width** this property is used to control the width of a border. The value of this property can either be given in pixels or using one of the following values: thin, medium, thick.

**border-style** You can control the style of a border using this property. Values listed on (pp. 310)

**border-color** You can specify the color of a border using either RGB values, hex codes, or CSS color names. (pp.311)

**border** allows you to specify the width, style and color of a border in one property (pp.312)

**padding** allows you to specify the amount of space between the content of an element and its border

**margin** controls the gap between boxes. You can specify the values for each side of a box using: margin-top, margin-right, margin-bottom, margin-left.

**centering content** If you want to center a box on the page you can set the left-margin and right-margin auto. (pp.315)

**Change inline/block** The **display** property allows you to turn an inline element in a block-level element or vice versa and can also be used to hide an element from the page. Values include: inline, block, inline-block, none.

### Hiding Boxes

**Visibility** this property allows you to hide boxes from users but it leaves a space where the element would have been. Values = **hidden** or **visible**

**Other properties** border-image, box-shadow, border-radius,  (pp.319-322)

**JavaScript**

Review Basic Javascript Instructions (70-73)

**Arrays* a special type of variable as they store more than one value. Example (pp.71)

**Chapter 4: "Decisions & Loops" from switch statements on (pp. 165-182)**

**Using Switch Statements** In the example on pp. 165, the purpose of the switch statement is to present the user with a different message depending on which level they are at. The message is stored in a variable called msg.

**Type Coercion & Weak Typing** If you use a data type JavaScript did not expect, it tries to make sense of the operation rather than report an error. 

**Truthy and Falsy Values** Truthy values are treated as if they are true. Falsy values are treated as if they are false.

**Checking Equality & Existence** Because the presence of an object or array can be considered truthy, it is often used to check for the existence of an element within a page.

**unary operator** returns a result with just one operand. (pp.168)

**short circuit values** logical operators are processed left to right. They short-circuit (stop) as soon as they have a result - but they return the value that stopped the processing (not necessarily true or false).

**Loops** Loops check a condition. If it returns true, a code block will run. The the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns false.

**3 types of Loops** For, While & Do While. (pp. 170)

Key Loop Concepts

**break** this keyword causes the termination of the loop and tells the interpreter to go onto the next statement of code outside of the loop.

**continue** tells the interpreter to stop the current iteration, and then update and check the condition again.

**Examples** (pp. 175-182)
