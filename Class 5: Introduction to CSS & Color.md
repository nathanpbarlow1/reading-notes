# Introducing CSS & Color

# Chapter 10: Introduction to CSS
	- CSS allows you to create rules that specify how the content of an element should appear.
	- For example, you can specify that the background of the page is cream, or paragraphs should appear in Gray using the aerial type face, or that all level one hitting should be in a blue, italic, times typeface.
	- A CSS rule contains two parts: a selector and a declaration.
		○ Selector
		○ Declaration
			§ P {font-family: Arial;}
		○ This role indicates that all <p> elements should be shown in the aerial type face
		○ Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.
		○ Declaration indicate how the elements referred to in the selector should be styled. Declarations are split into two parts, a property and a value, and are separated by a colon.
		○ CSS declaration sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semicolon.
			§ H1, h2, h3 {
				□ Font-family: Arial;
				□ Color: yellow;}
				□ Property value
			§ This rule indicates that all <h1>, <h2> and <h3> elements should be shown in the Arial typeface, in a yellow color
			§ Properties indicate the aspects of the element you want to change. For example, color, fonts, width, height and border.
			§ Values specify the settings you want to use for the chosen properties. For example, if you want to specify a color property then the value is the color you want the text in these elements to be.
	- Using External CSS
		○ <link>
			§ tref - this specifies the path to the CSS file, which is often placed in a folder called CSS or styles.
			§ type - this attribute specifies the type of document being linked to. The value should be taxed/CSS
			§ rel - this specifies the relationship between the HTML page and the file it is linked to. The value should be style sheet when linking to a CSS file.
			§ Example: 
				□ <link href="css/styles.css" type="text/css"
				□ rel="stylesheet" />
		○ CSS
			§ Body {
				□ Font-family: arial;
				□ Background-color: rgb (185, 179, 175);}
			§ H1 {
				□ Color: rgb (255, 255,255) ; }
	- Using Internal CSS
		○ <style>
			§ You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page.
		○ When building a site with more than one page, you should use an external CSS stylesheet.
			§ This allows all pages to use the same style rules, rather than repeating them in each page.
			§ Keeps the contents separate from how the page looks means you can change the styles use across all pages by altering just one file, rather than each individual page.
	- CSS Selectors
		○ Universal Selector	Applies to all elements in the document	• { } 
				• Targets all the elements on the page
		Type Selector	Matches element names	H1, h2, h3 { } 
				Targets the <h1>, <h2> and <h3> elements
		Class Selector	Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol	.note { }
				
				Targets any element whose class attribute has a value of note
				
				p.note { }
				
				Targets only <p> elements who class attribute has a value of note
				
				
		ID Selector 	Matches an element whose id attribute has a value that matches the one specified after the point or hash symbol	#introduction { }
		Child Selector	Matches an element that is a direct child of another	li>a { }
		Descendant selector	Matches an element that is a descendent of another specified element, not just a direct child of that element)	p a { } 
		Adjacent Sibling Selector	Matches an element that is the next sibling of another	H1+p { }
				Targets the first <p> element after any <h1>> element (but not other <p> elements)
				
		General Sibling Selector	Matches an element that is a sibling of another, although it does not have to be the directly preceding element	{ }
				Targets all elements on the page
			
			
	- How CSS Rules Cascade
		○ Last Rule: if the two selectors are identical, the latter of the two will take precedence.
		○ Specificity: if one selector is more specific than the others, the more specific rule will take precedence over more general ones. 
			§ Example: h1 is more specific than *
			§ P b is more specific than p
			§ P#intro is more specific than p
		○ Important: you can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element.
		○ Understanding how CSS rules cascade means you can write simpler sheets because you can create generic rules that apply to most elements and then override the properties of individual element that need to appear differently. 
	- Why Use External Style Sheets?
		○ All of your web pages can share the same style sheet. 
			§ This is achieved by using the <link> element on each HTML page of your site to link to the same CSS document.
			§ This means that the same code does not need to be repeated in every page
		○ If you want to make a change to how your site appears, you only need to edit the one CSS file and all of your pages will be updated.
	- Sometimes you might consider placing CSS rules in the same page as your HTML code. 
	- Online tools to show what a page looks like in multiple browsers
		○ Browsercam.com
		○ BrowserLab.Adobe.com
	- If you come across a CSS bug, you can check these sites:
		○ PositionIsEverything.net
		○ QuirksMode.org

## Summary: 
	- CSS treats every HTML element as if it appears inside its own box and uses rules to indicate how that element should look
	- Rules are made up of selectors (that specify the element the rule applies to) and declarations (that indicate what these elements should look like)
	- Different types of selectors allow you to target rules at different elements
	- Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.
	- CSS rules usually appear in a separate document, although they may appear within a HTML page.

# Chapter 11: Color

Foreground Color
	- The color property allows you to specify the color of text inside an element. 
	- You can specify any color in CSS in one of 3 ways:
		○ RGB Values: these express colors in terms of how much red, green and blue are used to make it up. For example: rgb (100,100,90)
		○ HEX Codes: these are six-digit codes that represent the amount of RGB, preceded by a pound or hash # sign. For example: #ee3e80
		○ Color Names: there are 147 predefined color names that are recognized by browsers. For example: DarkCyan

Background Color
	- Background color is specified the same way as foreground color, and if you don't specify a specific color than the background is transparent.

Understanding Color
	- HUE: who is near to the colloquial idea of color. Technically speaking however, a color can also have saturation and brightness as well as hue.
	- Saturation: saturation refers to the amount of gray in a color at maximum saturation, there should be no gray in the color. At minimum saturation, the color would be mostly gray.
	- Brightness: Brightness (or "value") refers to how much black is in a color. At maximum brightness, there would be no black in color. Minimum brightness, the color would be very dark.

CSS3: Opactiy
	- CSS three introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0, so a value of 0.5 is 50% opacity and 0.15 is 15% opacity.
	- The CSS3 rgba property allows you to specify color, just like you would a RGB value, but adds a 4th value to indicate opacity

CSS3: HSL Colors

CSS3: HSL & HSLA
Hsl, hsla

Hsl: alternative way to specify colors…the value of the property starts with the letters hsl, following by individual values inside parentheses for: HUE, Saturation, Lightness and adds a 4th value for transparency.

"a" stands for alpha, expressed as a number between 0 and 1.0. For example, 0.5 represents 50% transparency. 
