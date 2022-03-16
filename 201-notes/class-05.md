# Notes from Read: 05 HTML Images, CSS color and Text
[Home](README.md)
# Chapter 5, Images Pages 94-125
- how to add images to pages <br>
- choose the right format <br>
- optimizing images for the web <br>

adding images <br>
- img: element that calls in an image. <br>
- src: attribute that says where it is. <br>
- alt: attribute that discribes the image. <br>
- title: attribute that assignes a title to the page. <br>
- you can add height and weight attributes to manipulate the size. <br>

Rules for creating images <br>
- 1: save images in the right format <br>
- 2: save images at the right size <br>
- 3: measure images in pixels <br>
- you want the image to be saved at the same size you want it to be displayed. <br>
- cropping should look professional. <br>
- always set dimentions of an image by px. <br>

Transparency can be added to images

figure and figure caption
- figure: element that boxes an image with some related information. <br>
- figcaption: adds a little note under the image for a caption. <br>

## Images Summary
- the img element is used to add images to a web page. <br>
- you must always specify an src attribute to indicate the source of an image and an alt attribute to discribe the content of an image. <br>
- you should save images at the size you will be using them on the web page and in the appropriate format.
- Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

# Chapter 11, Color Pages 246-263
- how to specify colors
- color terminology and contrast
- background color

Color and Backgound color
- rgb values: three sets of numbers between 0-255 that represent color. <br>
- hex codes: six-didget hexadesimal assignments for colors. <br>
- color names: just that, a color for ones name. <br>
- background color: specifies the actual background instead of the text. <br>

Contrast
- contrast is how light and dark the background is compared to the forground. <br>
- opacity: makes whatever selected see through. <br>

HSL colors
- hue: represents a color circle to pick from. <br>
- saturation: the amount of gray in a color. <br>
- lightness: amount of white or black in a color. <br>

## Color Summary
- color not only brings your site to life, but also helps convey the mood and evokes reactions. <br>
- there are three ways to specify colors in CSS: RGB values, hex codes, and color names. <br>
- color pickers can help you find the color you want. <br>
- It is important to ensure that there is enough contrast between any text and the background color. <br>
- CSS3 has introduced an extra value for RGB colors to indicate opacity. It is know as RGBA. <br>
- CSS3 also allows you to specify colors as HSL values with an optional opacity value. it is known as HSLA. <br>


# Chapter 12, Text Pages 264-299
- size and typeface of text
- bold, italics, capitals, underlines
- spacing between lines, words, and letters

typeface terminology
- serif: serif fonts have extra detail on them. <br>
- sans-serif: have straight ends to letters. <br>
- monospace: like code, they are all equal sized. <br>
- cursive: fonts that look like strokes of a pen. <br>
- fantasy: usually decorative fonts often used for titles. <br>

text definitions
- font-family: used to declare what typeface you will be using. <br>
- font-size: how big or small you want the font to be. <br>
- type size scale: measured in px, % and ems. <br>
- font-weight: how bold a font will appear. <br>
- font-style: can add things such as italic. <br>
- text-transform: can change upper and lower case letters. <br>
- text-decoration: adds underline or strikes, or linethoughts. <br>
- line-height: basically adds padding. <br>
- letter-spacing/word-spaceing: self explanitory. <br>
- text-align: used to direct where text should go in an element. <br>
- vertical-align: same thing but virtically. <br>
- text-shadow: adds a shadow to the background. <br>

styling links
- link: style for links that have not been visited yet. <br>
- visited: style for links that have been visited. <br>

responding to others
- hover: applies when the user hovers over an element. <br>
- active: when the element is being activated. <br>

attribute selectors on page 292

## Text Summary
- there are properties to control the choice of font, size, weight, style, and spacing.<br>
- there is a limited choice of fonts that you can assume most people will have installed. <br>
- if you want to use a wider range of typefaces there are several options, but you need to have the right license to use them. <br>
- you can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented. <br>
- you can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link. <br>