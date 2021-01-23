## HTML

### Chapter 5: "Images" (pp.94-125)
``<img>`` this is an empty element, meaning there's no closing tag. It must carry the ``<src`` and ``<img>`` attribute>
Also mentioned in 413-420.
``<src>`` this tells the browser where it can find the image file. This will usually be a relative URL pointing to an imahe on your own site.
``<alt>`` this provides a text description of the image which describes the image if you cannot see it.
``<title>`` you can also usew this attribute with the ``<img>`` element to provide additional information about the image. Most browsers will display the content of this attribute in a tooltip when the user hovers over the image.

``<height>`` this specifies the height of the image in pixels.
``<width>`` this specifies the width of the image in pixels.  
**JPEG** file format to use when you have a  picture with many different colors
**GIF OR PNG** file format to use when few colors or large areas of same color.

**Where to place images in your code** (options below)

1) Before a Paragraph
2) Inside the Start of a Paragraph
3) In the Middle of a Paragraph

### Chapter 11: "Color" (pp.246-263)
``color`` this property allows you to specify the color of text inside an element
``background color``CSS treats each HTML eleemtn as if it appears in a box, and the ``background-color`` property sets the color of the background for that box.
``opacity`` this property allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0.
**HSL Colors** CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values. (pp.255)
``hsl`` this property contains the following three values to represent color:
hue, saturation, lightness - example: ``hsla(0, 100%, 100%, 0.5);}``
``hsla`` same as ``hsl`` plus a fourth value for transparency, the a stands for alpha.
``alpha`` expressed as a numbere between 0 and 1.0.
**RGB Values** these express colors in terms of how much RGB are used to make it up.
**HEX Codes** these are six-digit codes that represent the amount of RGB in a color, proceeded by a pound or hash # sign.
**Color Names** there are 147 predefined color names that are recognized by browsers. For example: DarkCyan
**Example Color Code** (pp.257-260)

### Chapter 12: "Text" (pp.264-299)
``font-family`` property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rules applies. Multiple founts can be added and separated by a comma, with the browser choosing whichever format the user has installed on their computer from left to right: ``font-family: Georgia, Times, serif;}
``font-size`` this property enabkles you to specify a size for the font. The most common ways to do this is by Pixels and Percedntages
``font-family`` The specifies the name of the font. This name can then be used as a value of the font – family property in the rest of the style sheet. (pp. 277)
``src`` The specifies the path to the font. In order for this technique to work in all browsers, you will probably need to specify paths to a different version of the font, as shown on the next page. (pp. 277)
``format`` The specifies the format that the font is supplied in.
``font-weight`` This property allows you to create bold text. There are two values of this property commonly takes: ``normal`` this text causes the text to appear at a normal weight and ``bold`` this causes text to appear bold.  (pp.279)
``font-style`` If you want to create italic tax, you can use this property, which takes three values: ``normal`` This causes text to appear in a normal style. ``italic`` This causes text to appear italic. ``Oblique`` This causes the text to appear oblique. (pp. 280)

**Choosing a typeface for your website** (pp.269)
**Techniques that Offer a Wider Choice of Typefaces** (pp.271-272)
**Typeface terminology** Serif, Sans-serif and Monospace.
**Type scales and Units of Type size** (pp. 275-276)
**Understanding Font Formats** (pp. 278)
**EMS** an em is equivalent to the width of a letter m.
**Weight** Light, medium, bold, black
**Style** Normal, Italic, Oblique
**Stretch** Condensed, Regular, Extended



