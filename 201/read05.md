## Images
 - images are important part of the website they defin a good website from the bad ones.
 - images should be : *Relvent*, *convy informations*, *convey the right mood *,*be recognizable*,*fit in the Color palette*.
 - Storing Images on the web site; its a* good practis* to Keep all images in a folder(Images) in the website. 
 - we can seprate images used for every purpose in a *supfolder* .
 - Adding Images we use an `<img>` element.it must carry the following attributes :
   * `src` that tells the broweser where to find the image file.
   * `alt` provides the text description of the image if we cannt see it.
   * `title` to provide additional information about the image.
   * `width ` to spacify the width of the image in pixels .
   * ` hight` to spacify the hight of the image in pixels.
 - We can place an image in the code and it will affect where it will show.
   * befor a paragraph ; the paragraph starts on a new line after the image.
   * inside the start of a paragraph ; the first row of text align with the buttom of the image.
   * in the middle of a paragraph;the image is placed between the words of the paragraph.  
- `align` ; to indicate how other parts of the page should flow around image.it takes `left` and `right` values.
- To align it Vertically ; we use `top`,`middle`.`bottom`.
### three rules to creat images
1. save images in the right format
2. Save images in the right size.
3. Use the Correct resolution.
- tools to edit images by using tools  such as AdopePhotoshop.
- Images Dimension.The images you use on your website should be saved at the same width and height that you
  want them to appear on the page.
- when cropping images it is important not to lose valuble information.
- we can use `portrait` `crop` `add extra space`.
- Image Resolution;Images created for the web should be saved at
   a resolution of 72 pp.
- Vector images differ from bitmap images and are resolution-independent. Vector images are
   commonly created in programs such as AdobeIllustrator.
- Animated GIFs show several frames of an image in sequence and therefore can be used to
   create simple animations.
Creating an image that is partially transparent
(or "see-through") for the web involves
selecting one of two formats:1.transparent gIf;2.png
- we need to check the size of an existing image before creating a new one to replace it.

## Figure and Figure Caption.
- `figure` to contain images and their captionso the two are associted .
- `figcaption` to allow web page authors to add a caption to an image.

## Chapter 11: Color 
- the color property allows you to spacify the color inside an element.
- RGB values ; shows how much red,green ,blue are used to make it up.
- HEX codes; these are 6 digit codes that represent the amount of red green and blue in a color. proced by a pound or hash #ee3e80.
- color name ; like darkcayn -background-color; allows to set the background color for a box .
- chosing color be choosing its RGB value or HEX code or by its name.
  contrast
- when picking foreground and backgrounf colors its important to ensure that there is enough contrast for the text to be legiable.
- Opacity proparity ; which allows you spacify the opacity of an element. the value is between 0.0 and 1.0
   HSL color
- its a new way to spacify colors using hue,saturation,and lightnessvalue .
- hs1 its an alternative way to spacify colors .the value of the proparty satrts with letter hs1 followed by indivusal inside paranthisis.
- HUE is expressed as an angle between 0 and 360.
- saturation is expreseed as a precentige.
- lightnes is expressed as precentage.
- Alpha is a number between 0 and 1.0

## chapter 12 : Text's

structural markup :the elements that are used to describe heading and elemnts
Semantic markup :provieds extra information as where to emphasis is placed in a sentence.
Headings:
### HTML uses six levels of headings
- `<h1>` is used for main headings
- `<h2>` is for subheadings,for subheading we use other  sunheading.
- the browser shows heading based on their size other
### Paragraphs 
- to creat a pharagraph sorrownd the text with an opening tag and closing tag of <p>
### bold and italic
- to make a word bold we use `<b></b>` sourownding the text.
- to make the word apper italic we use `<i></i>`.
### supscript& superscripts 
- `<sup>` its used to contain charechters that should be suoerscript such s suffix of dates or mathmatical concept.
- `<sub>` its used with foot notes or chemichal formulas.
 ![example](201/read02.jpg)
### white space 
- if the browser come across 2 or more spaces next to each other it displays one space.
### Line breaks & Horizantal rules 
- `<br/>` to move to a new line inside the middle of pharagraph.
- `<hr/>` to creat a break between themes.
### Visual Editors & thier code view 
- **viusal editor** : they resemble word processor
  -there are few fetures that are common to most eitors.such as:
   * Headings; created by highliting text then using a drop down box to selsect heading
   * Bold and italic; created by highliting some text and pressing a **B** or **I** button.
   * New Paragrph; created using the return and enter key
   * Line break; is cretaed by presseing the shift key and return key.
   * Horizantal rulers are created using a button with a straight line on it .
- **code views** shows the code created by the visual editor so you cam manually edit it.
- Semantic markup; used to show some text elements that provide extra information but they are not intended to change the strucure of the page.
- `<strong>`it indicates that the content has strong importance .
- `<em>` indicates emphisis that subtly changes the meaninf of a sentance.
- Qutations :
 * `<blockquote>`is used for longer quotes that take an entire paragraph.
 * `<q>` used for shorter quotes.
- `<abbr>` is used when using abbreiviation or acroynym.
- `<cite>`is used when refrancing a piec of work such as a book.
- `<dfn>` when you explain new terminology.
- `<address>` to conatin contact details for the author of the page.
- `<ins>` to show contact that has been inserted into document.
- `<del>` shows text that has been deleted from the text.
- `<s>` indicates smth that is no longer accurate.