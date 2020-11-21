# Class 4 Notes: Process & Design, Structure, HTML5 layout and Extra Markup.

Elements = HTML code made up of characters that live inside angled brackets. Tells the browser something about the information that sits between its opening and closing tags.
Tags =
	- part of elements, an opening tag and a closing tag, i.e. <p> </p>
	- They act like containers

## Attributes = 
	- provides additional info about the contents of an element.
	- They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign
	- <p lang="en-us">Paragraph in English</p>
		○ The attribute name ("lang") indicates what kind of info you are supplying about the elements content. It should be written in lowercase.
		○ The value is the information or setting for the attribute. It should be placed in double quotes. 
		○ Here an attribute called lang is used to indicate language used in this element. The value of this attribute on this page specifies it is in US English.
<body>
	- Content
	- Everything within this tag will be displayed
<head>
	- This element contains info about the page (rather than info that is shown within the main part of the browser window that is highlighted in blue on the opposite page).
	- You will usually find a <title> element inside the <head> element

HTML
	- Hypertext Markup Language
	- Hypertext refers to the fact that HTML allows visitors to move from one page to another quickly and easily.
	- A markup language allows you to annotate text, and these annotation provide additional meaning to the contents of a document.

## The Evolution of HTML
	- I've been aware of some of the history of HTML, but I didn't know much about XHTML 1.0. 
	- XHTML 1.0 was release in 2000. XML was published in 1988 and it's purpose was to allow people to write new markup languages. Since HTML was the most widely used markup language around, it was decided that HTML 4 should be reformulated to follow the rules of XML and it was renamed XHTML. 
	- Some new, more strict rules were put into place, including:
		○ Every element needed a closing tag, attribute names were in lower case, all attributes required a value, plus more…
	- There were 3 different versions of XHTML (Strict, transitional, and Frameset)
	- HTML5 is actually WIP.
	
### Other Definitions:
	- DOCTYPES: this is a declaration  to tell a browser which version of HTML the page is using <!DOCTYPE html>
	- Comments in HTML: <!-- --> this code allows for comments, which will not be visible to the browser. Helpful for someone who hasn't looked at the code before, or even yourself if it's been a long time since creation. 
	- ID Attribute: every HTML element can carry an attribute. Used to uniquely identify that element from other elements on the page. It's important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).
		○ Giving an element a unique identity allows you to style it differently from any other instance of the same element on the page. 
		○ Known as a global attribute because it can be used on any element. 
		○ Example <p id="pullquote">
	- Class attribute: This allows you to identify several elements as being different from the other elements on the page. 
		○ Its value should describe the class it belongs to. 
	- Block elements: these elements will always appear to start on a new line in the browser window. 
		○ Examples: <h1>, <p>, <ul>, and <li>.
	- Inline elements: they always appear to continue on the same line as their neighbouring elements. 
		○ Examples: <a>, <b>, <em>, and <img>
		○ <em> = Italicize
		○ <b> = bold
	- <div>: this element allows you to group a set of elements together in one block-level box.
		○ Using an id or class attribute on the <div> element will allow you to create CSS style rules to indicate how much space the <div> element should occupy on the screen and change the appearance of all the elements contained within it.  
		○ Examples: 
			○ you might create a <div> element to contain all of the elements for the header of your site (the logo and the navigation.
			○ Or, you might create a <div> to contain comments from visitors
	- <span>
		○ Acts like an inline equivalent of the <div> element and is used to:
			1) Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
			2) Contains a number of inline elements
		○ Most common reason to use it is so they can control the appearance of the content of these elements using CSS.
	- <iframe>
		○ Like a little window that has been cut into your page--and in that window you can see another page. 
		○ Example: 
			○ Embedded Google Maps
		○ <iframe> attributes:
			○ src: specifies the URL of the page to show in the frame
			○ height: specifies the heigh of the iframe in pixels. 
			○ width: specifies to the width of the iframe in pixels
	- Scrolling: not supported in HTML5, indicates whether the iframe should have scrollbars.
	- Frameborder:  also not supported in HTML5, indicates whether the iframe should have a border or not. 0 = no, 1 = yes.
	- Seamless: applied to an iframe where scrollbars are not desired. 
		○ Does not need a value
		○ Authors commonly give it a value of seamless
	- <meta>
		○ Lives inside the <head> element and contains info about the page
		○ Not visible to users, tells search engines about the page, who created it, and whether or not it is time sensitive (can expire).
		○ Empty element (does not have a closing tag).
		○ Most common attributes are name and content attributes, name attribute is the property you are setting, and the value of the content attribute is the value that you want to give this property. 
		○ Description: used by search engines to understand what the page is about, should be limited to 155 characters. 
			○ <meta name="description"
				□ Content="An Essay on Installation Art" />
		○ Keywords: contains a list of comma-separated words that a user might search on to find the page, this no longer has any noticeable affect on how search e ngines index your site. 
		○ Robots: indicates whether a search engine should add this page to their search results. 
			○ "no index" = page should not be added.
			○ "no follow" = should add but not any pages it’s linked to.
				□ <meta name="robots"
					® Content="no follow" />
		○ <meta> element also uses the http-equiv and content attributes in pairs
			○ Author: defines the author of the page
			○ Pragma: prevents the browser from caching the page
			○ Expires: because browsers often cache the content of the page, the expires option can be used to indicate when the page should expire (and no longer be cached). Date must be specified in the format shown: Fri, 04 Apr 2014 23:59:59 GMT"
		○ Escape characters: <, >, &, ", ',',", X, etc. (page 194)
		○ <aside>
			- Inside <article>
				□ Should contain info that is related to the article but not essential to its meaning.
				□ Example: a pullquote or glossary might be considered as an aside to the article it relates to.
			- Outside <article>
				□ Acts as a container for content that is related to the entire page
				□ Example: it might contain links to other sections of the site, a list of recent posts, a search box, or recent tweets by the author.
		○ <figure>
			○ Used to contain any content that is referenced from the main flow of an article (not just images)
			○ Examples:
				□ Images
				□ Videos
				□ Graphs
				□ Diagrams
				□ Code samples
				□ Text that supports the main body of an article
		

