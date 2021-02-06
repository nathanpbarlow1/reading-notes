# HTML Chapter 7: "Forms" (p.144-175)

**Forms** HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site. Whether you are adding a simple search box to your website or you need to create more complicated insurance application, HTML forms give you a set of elements to collect data from your users.

**Adding Text** see options below

- Text Input
- Password Input
- Text Ares (multi-line)

**Making Choices** see options below

- Radio buttons
- Checkboxes
- Drop down boxes

**Submitting Forms** see options below

- Submit buttons
- Image buttons
- File upload

**How Forms Work** See steps below

1) The user fills in a form and then press a button to submit the information to the server.
2) The name of each form control is sent to the server along with the value of the user enters or selects.
3) The server processes the information using a programming language such as PHP, C#, VB.net, Or Java. It may also store the information in a database.
4) The server creates a new page to send back to the browser based on the information received.

- You should never change the name of a form control in a page unless you know that the code on the server will understand this new value.

## Form Structure

``<form>`` Form controls live inside this element, and should always carry the action attribute and will usually have a method an ID attribute to.
``action`` Every form element requires an action attribute. It's value is the URL for the page on the server that will receive the information in the form when it is submitted.
``method`` Forms can be sent using one of two methods; get or post. **get method** With this method, the values from the former added to the end of the URL specified in the action attribute. This method is ideal for: short forms (such as search boxes), or when you are retrieving data from the web server (not sending information that should be added to or deleted from a database). **Post method** And this method the values are sent and what are known as HTTP headers. As a rule of thumb you should use the post method if your form: allows users to upload a file, is very long, contain sensitive data like passwords, ads information to, or deletes information from, a database.
``<input>>`` This element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.
``type="text"`` When the type attribute has a value of tax, creates a single line text input.
``Type=radio"``
``type="hidden"``
**Checkbox**(pp.156)
**Drop Down List Box** (pp.157)
**Multiple Select Box** (pp.158)
**File Input Box** (pp.159)
**Submit button** (pp.160)
**Image  Button** (pp.161)
**Grouping Form Elements** (pp.164)
**HTML Form Validatiopn** Supported by Chrome and Operate, so many devs still use javascript to ensure older browser support. 
**HTML5: Email & URL Input** (pp.167)
**HTML5: Search Input** (pp.168)

``name`` When a user enters information into a form, the server needs to know which form of control each piece of data was entered into. Therefore, each form controls a name attribute. The value of this attribute identifies the form control in ascent along with the information they enter to the server.
``maxlength`` You can use the max length attribute to limit the number of characters a user may enter into the text field. It's values the number of characters they may enter. For example, if you were asking for a year, the max length attribute could have a value of four.
**Password Input**``<input type="password">`` When the type attribute has a value a password it creates a text box that acts just like a single line text input, except the characters are blocked out. They are heading in this way so that if someone is looking over these are sold or they cannot see sensitive data such as passwords.
``<nane>`` The name attribute indicates the name of the password input, which is sent to the server with the password the user enters.
``<textarea>`` This element is used to create a multi line text and put. Unlike other input elements this is not an empty element. It should therefore have an opening and closing tag. Any text that appears between the opening and closing tags will appear in the text box with the page loads.
``size`` The size actually it should not be used on new forms. It was using older forms to indicate the width of the text input. In any new forms you're right, CSS should be used to control the width of form elements.

### Chapter 14: "Lists, Tables & Forms" (pp. 330-357)

**Bullet Point Styles** (pp.333)
**Images for Bullets** (pp.334)
**Positioning the Marker, list-style-position** (pp. 335)
**list-style** (pp.336)
**Table properties** (pp.337)
**Styling text inputs** (pp.342)
**Styling Submit Buttons** (pp.343)
**Cursor styles** (pp. 347)

### Javascript: Chapter 6: "Events" (pp.243-292)

1) **Interactions create events**
2) **Events trigger code**
3) **Code Responds to Users**

**Different Event Types** (pp. 246)

NEED TO TRANSFER OVER REMAINING CHAPTER 6 Notes to MD