## CSS allow you to creat rules that spacify how the content of an element should apper 
### the key to understand HTML is to imaginr an invisible box around each HTML element .
- block level elements looks like they start on anew line like 
(h6> <p> <div>
- inline elements flow through the text and dont appear on a new line like;
<b>;<em>,<span>.
- CSS rule contains of 2 sections a selector and decleration
ex : p{font-family:Arial;}
- CSS declaration is inside curly bracitse and ismmade of 2 parts:
proparity and a value 
ex:
h1,h2,h3{color:yellow;}

#### <link> this element is used in html to tell the browser where to find the CSS file used to style the page
- its also an empty element that doesnt need a closing tag
- its inside the <head> element 
- Href is path to the css file 
- type ; spacified the type of the document being linked to it should be text/css
- rel ; spacifies the relation between html and the file its linked to ,the value should be style sheet
- using an internal CSS could be included within HTML page,
by palcing them inside <style> element 
- when building a site with many pages ,we should use external CSS style sheet

#### CSS selector 
- CSS selectors are case sensitive 
they must match names and attributes values exactly:

universal selector .....tragets all elementts in the page .... *{}
type selctor............Matches elements name .................h2 .h2{}
class selector .........matches an element whose class attribute has a value spacified after the period... .note{};p.note{}

### if there are more than two rules that applay to the same element , the latter of the two will tacke procidance 
- if one selction is spacifed than the other the spacified will tacke precedance
- !important this indicates it should be considerd more important .


## color chapter 11
- the color property allows you to spacify the color inside an element.
- RGB values ; shows how much red,green ,blue are used to make it up.
- HEX codes; these are 6 digit codes that represent the amount of red green and blue in a color. proced by a pound or hash #ee3e80.
- color name ; like darkcayn
-background-color; allows to set the background color for a box .
- chosing color be choosing its RGB value or HEX code or by its name.

### contrast
- when picking foreground and backgrounf colors its important to ensure that there is enough contrast for the text to be legiable.
- Opacity proparity ; which allows you spacify the opacity of an element.
  the value is between 0.0 and 1.0
### HSL color 
- its a new way to spacify colors using hue,saturation,and lightnessvalue .
- hs1 its an alternative way to spacify colors .the value of the proparty satrts with letter hs1 followed by indivusal inside paranthisis.
  - HUE is expressed as an angle between 0 and 360.
  - saturation is expreseed as a precentige.
  - lightnes is expressed as precentage.
  - Alpha is a number between 0 and 1.0

## Functions p 88 94
- functions aqnd methods 
  - functions are a series of staments that have been grouped togther beacuse they preform a spasific task
  - a method is the same except methods are created inside and are part of an object.
  - objects used to creat models of the world using data ,made up of properites and methods 
  - built in objects ; the broweser comes with a set of objects that act like toolkit for intractive web pages.
  