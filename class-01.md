# Reading Notes for Class 01

## Introduction (pp.2-11)

## HTML Chapter 1: “Structure” (pp.12-39)

- **elements** characters that live inside angled brackets. 
 
- **tags** two tags (opening and closing) form an element. 

- **html** this opening tag indicates that anything between it and a closing tag is HTML code. 

- **body** tag indicates that anything between it and the closing tag should be shown inside the main browser window

- **head** tag contains info about the page. You will usuaully find a <title> element inside the <head> element
	
- **title** the contents of this element are either shown in the top of the browser, or on the tab for that page. 
  
 
  
  
## HTML Chapter 8: “Extra Markup” (p.176-199)

- **comments** <!--insert comment here -->

- **id attribute** every HTML Element can carry that idea attribute. 
    It is used to uniquely identify the element from other elements on the page. It's value should start with the letter or an underscore It is important that no two elements on the same page have the same value for their ID attributes. 
    Giving an element a unique identity allows you to style it differently from any other instance of the same element on the page. For example, you might want to assign one paragraph within the page a different style from all of the other paragraphs.
    The ID attribute is known as a global attribute because it can be used on any element.
    
-**class attribute** Sometimes, rather than uniquely identifying one element within a document, he will wanna way to identify several elements as being different from the other elements on the page. For example, you might have some paragraphs of tax that contain information that is more important than others and want to distinguish it between these elements, or you might want to differentiate between links that point to other pages on your own site and links that point to external sites.

-**block elements** These are elements that appear on a new line in the browser window.
  
-**inline elements** Some elements will always appear to continue on the same line as their neighboring elements, these are known as inline elements.
  
-**div** this element allows you to group a set of elements together in one block level box. For example, you might create a <div> element to contain all of the elements for the header of your site, or you might create a <div> element to contain comments from visitors.

-**span element** the <span> element Acts like an in-line equivalent of the <div> element. It is used to: 1) Container section of text where there is no suitable element to differentiate it from its surrounding text. 2) Container number of in-line elements. The Most common reason why people use <span> Elements is so that they can control the appearance of the contents of these elements using CSS. 

-**iframe** <iframe>
Like a little window that has been cut into your page--and in that window you can see another page. 
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
  
- **meta** <meta>
	○ Lives inside the <head> element and contains info about the page
	○ Not visible to users, tells search engines about the page, who created it, and whether or not it is time sensitive (can expire).
	○ Empty element (does not have a closing tag).
	○ Most common attributes are name and content attributes, name attribute is the property you are setting, and the value of the content attribute is the value that you want to give this property. 
	○ **Description** used by search engines to understand what the page is about, should be limited to 155 characters. 
		○ <meta name="description"
			□ Content="An Essay on Installation Art" />
	○ Keywords: contains a list of comma-separated words that a user might search on to find the page, this no longer has any noticeable affect on how search engines index your site. 
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


## HTML Chapter 17: “HTML5 Layout” (pp.428-451)

-**article** <article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.
  
-**aside** <aside> element has two purposes, depending on whether it is inside an <article> element or not.When it's used inside an <article> element, it should contain info that is related to the article but not essential for its overall meaning. For example, a pullquote or glossary might be consider as an aside to the article it relates to. When it's used outside of an <article> element, it acts as a container for content that i srelated to the entire page. (436)
  
-**section** <section> element groups related content together, and typically each section would have its own heading.

-**hgroup** <hgroup> element is used to group together a set of one or more <h1> through <h6> elments. 
  
-**figure** <figure> It can be used to contain any contact that is referenced from the main flow of an article. The figure element should also contain a <figcaption> Element which provides a text description for the content of the figure element. In this example, you can see a figure has been added inside the article element. Page 439.


## HTML Chapter 18: “Process & Design” (pp.452-475)

## Questions to ask when building a site

-**who is the site for?**
-**why people visit your site?**
-**what your visitors are trying to achieve?**
-**what information your vistitors need**
-**how often people will visit your site**

-**site maps** the aim is to create a diagram of the pages that will be used to structure the site.

-**visual hierarchy** refers to the order in which your eyes perceive what they see. It is created by adding visual contrast between the items being displayed. Items with higher contrast are recognized and processed first. 

