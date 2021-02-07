## TEXTs:
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

## Chapter 10 introducing CSS.
- the key in understanding css is to think that to imagin an invisable box around every HTML element.
- **Block elements** they start on a new level like `<h1><p> <div>`
- **Inline elements ** they continue on the same line like `<b> <em> `.
- CSS allows you to creat rules to control how the box and its content is presented 

### styles examples :
1. boxes : width ,hight, borders(color width and style), background color...etc
2. Text : size,typeface, color,italics...etc
3. Spacific such as lists tables and forms.

- CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration 
![declration of css style](201/read022.jpg)
- CSS diclration is set in curly brackets and each is made of two parts : proparity and value 
- using external CSS :
 * `<link>`its used to tell the browser wher to find the css file used in the page.
 * href; it spacifies the path to the CSS file .
 * type; spacifies the type of document being linked to.
 * rel; to spacify the realtionship between HTML and the file it is linked to.
- using Internal CSS:
 - using within an HTML page by placing them inside a <style> element,which usually sits inside the
   `<head>` element of the page.
 CSS  selector :
1. Universal Selector applies to all elements in the document 
2. Type selector matches element names 
3. class selector matches an element with the same class selector
4. ID selector Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol.
5. child selector matches an element that is a direct child.
6. descendant SeLector Matches an element that is a descendent of another specified element (not just a direct child of that element)
7. adjacent Sibling SeLector Matches an element that is the next sibling of another.
8. generaL Sibling SeLector Matches an element that is a sibling of another, although it does not have to be the directly preceding element.

## How Css rules cascade 
- last rule ; if 2 selctors are identical the latter of the two will take precedance.
- Spacify if one selector is more spacific than others the more spacific rule will take presedance.
- Important you can add **!important **
- inhertance; if you use a proparty in the boady it will applay to most elements.
##why use external atyle sheets?
- all of your web pages can share the same style sheet.
- its easer to use when alternating an element in the page.





# Chapter 2 :Basic JavaScript Instrustions.
## statments
 - script is a series of instuctions that the computer follow;
   each indivisual instruction is a **statment** .
 - statment should end with a  ; .
 - the curly braces indicates the start and end of code block.
 - J.S is case sensitive 
 - Statments are instructions and each one starts at a new line.
 - Comments are used to help understand your code using:
     * multi line comment :  `/* ....*/` .
     * single line comment : `//`

## Variables 
 - its a place where the script is temporarly stored.
 - the variable should have a name that explains what its for.
 - we declare a variable using *var* and a name for the variable.
 - we assign a valut to the variable using `=` sign.

## Data types 
1. Numeric values such as 0.75
2. Strings; contains of letters and chrechters 
3. Boolean ; that return a true or false.

- we can store numbers in variables
- we can store strings in variables:
   * strings is placed between qoute marks single or doubled
   * qoutes should be stright not curly 
   * strings must always be written in a single line.
   * *escaping technich* is used when we want to use qoutes marks in the string.
- we can store a boolean in a variable.
- we can change the value of a variable later in the script.

### Rules for naming a variable :
1. the name must begin with a letter,$,_ but never a number.
2. it can contain $ _ and numbers 
3. we cant use reserved words.
4. all variables are case sensitive.
5. use a name that describes the values stored in it.
6. use *CameCase* if the var name is two name or more.


## Arrays
- arrays are special kind of variables that store list of values>
- we use it when we use a list of values that are related to each other.
- when creating an array we dont need to spacify how many values it hold.
- values in arrray are separated by commas.
- we creat an array like a variable, its values are held between square bracts [].
-array constructor. This uses the new keyword followed by Array();
  The values are then specified in parentheses (not square brackets), and each value is separated by a comma.
- values in arrays are accessed as ifs a numbered list starrting from 0 .
  * Each item in an array isautomatically given a number called an index.
  * To retrieve item on the list, the array name is specified along with the index number in square brackets.
  * Each array has a property called length, which holds the number of items in the array.

## Expressions
- expression evaluates into (results in) a single value.
  * EXPRESSIONS THAT ASSIGN AVALUE TO A VARIABLE.
  * EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE.
## operators 
1. assignment operators 
2. Arithmatic operators 
![Arithmatic Operators](201/read0222.jpg)

3. comparison operators 
4. logical operators 
5. string operators 


## Chapter 4: Decisions and Loops

in order to determin which path the script takes we need to :
1.EVALUATIONS You can analyze values in your scripts to determine
whether or note they match expected results.
2. DECISIONS Using the results of evaluations, you can decide which path your 
script should go down
3.LOOPS There are also many occasions where you will
want to perform the same set of steps repeatedly

- flow charts help decide the path the script follows
- we set a condition and write codes for both options.
- there are 2 componants of a decsion :
   1. an expression is evaluated 
   2. a conditioal statment that says what to do in a given situation.

you can compare value to what you except it might be.
1.  == is equal to (it compares 2 values numbers strings or Boolean)to see if they are the same 
    'hello' == 'goodbye' return false 
     'hello' == 'hello' returns true 
2. != is not equal to cheacks two values to see if they are NOT the same .
     'hello' != 'goodbye' return true
     ' hello' != 'hello' return false
3. === strict equal to checks both datatype and value are the same '3'=== 3 return false; not the same data type
     '3' === '3' returns true ; same data type and value .
4. !== strict not equal to comparest 2 values to cheackboth data type and value are NOT the same
     '3' !== 3 returns true
     '3'!=='3' returns false
5. > greater than 
     4>3 returns true 
6.< less than 
     4<3 returns false
7.>= greator than or equal 
     4>= 3 returns true 
8. <= less than oor equal 
     4<=3 returns false  

### programmers return tho testing of a condition as EVALUATING. 
- they usually result in a true or false.
- evey value can be treated as  true or false even if its not a boolean
- in short circuit evaluation; conditions might not need to run .\
 

## Logical Operators 
unlike comparison operators that return one value , the logical operators allow you to
compare the result of more than one comparison operator 
1. && cheacks if both expressions on the side return true.
 - t && t returns t
 - t && f returns f
 - f && t returns f
 - f && f returns f

2. || logical or this test at least one condition.
  - `t || t` returns t
  -` t|| f` returns t
  - `f||t` returns t
  - `f || f` returns f
3- `! `logical not , this takes a single boolean value and inverts it 
  - `!T` returns F
  - `!F` returns T 

using IF statment 
 if (coondition){
   code to be excuted if true
   } else if {
    code excuted if not true
   } 