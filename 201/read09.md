## Chapter 7: Forms 
- what is Forms : its a printed document that has spaces where users fill information.
- the most known form is Google search HomePage, also when regestirng into a website, shoping...
- types of Forms :
  1. Adding text : 
    * text input ; where it takes a single line of information.
    * Password; where it takes charechters and mask them
    * Text area; it takes longer texts such as comments
  2. Makaing choices:
     *Radio buttons
     *Check boxes
     *drop down lists 
  3.Submitting forms:
    * submit buttons
    * Image buttons
    * File upload
## How forms work ?
  **first** user fills info then submit by clicking a button it sends the info to the server. 
  ** Second** the name of the form anf the submission info is sent to the server.
  ** Third** the server processes the info. using programming languages, it may store them in DataBase.
  ** Forth** the server creates a new page and send it back to the user based on the info it recived.
-  server could have diffrent form controld to get diffrent inforamtion; based on the input data it correspond with form element.
- ** Form Structure**:
  - `<form>`:usually it hold an *ID and Methods* also carry *action*
    - every form requiers an action attribut the value is the URL for the page on the server which will recive the information when submitted.
    - method : either get ot post 
      * get makes values from the form to be added in URL that is spacifed in **action** attribute.its commonley used in search boxes and when retriving info from servers
      * post the values are sent as HTTP header,we can use it when :let user upload a file or when writing passwords or add info or delet from data base.
  - `<input>`  use dto creat diffren form conntrols , it determin what kind of input it will creat.
  - `type ="test"` it creates a value of text.
  - `name` the name of the form for server.
  -`MaxLenght` is used to determin how many charechter allowed in text field.

  - The Password Input
   - `type="password"` its similar to single line text input but the chrechters are blocked out.
   - `name` indicates the name of password input that goes to server with the entered password.
   - ` size,maxlenght` it carrys the size and max lenght.  
 - text area
   - it takes multi line input 
   - it has an ending tag
   - the message written will go to the  server 
 - Radio buttons
   -`type="radio"` allow user to pick one option.
   - `name` the server recive the button user choose
   - ` value` the sent value to the server.
   - ` checked` used to tell which value should be selected when page loads .
 - Cheack box:
   - `name` is sent to server  when the user select a box.
   - `value` the sent value to the user .
   - `checked` indicates which box should be checked when page loads.
 - fle input text:
    - `type="file"` creates a box like text input followed by a browse button.
 - Submit button :
    - type="submit" used to send submission info to server
    - `name` it uses it but it doesnt need it in this case
    - `value` used to control what appers on the button.
 - Image button:
    - `type="image"` we use it and can give it attribute values like src,width ,hight 
 - `<button>` it addes a button to the page we can control how it looks and what text is inside.
 - `type:"hiddin" ` used by devlopers to show which page user was on when submitted.
 - `<label>` gives a form a name so user can tell the puurpose of it .
 - label can bs used in 2 difffrent ways: 1. wrap around text and description and 2. kept separate from control and use 
 - `for` states which form control the label belongs to.

 - Grouping form element 
  - `<fieldset>` in order to group form controls toghther .
  -`<legend>` it comes after the `<fielset>` and contains a caption to help identify the purpose of the group of form controls.

 - Form Validation:when the user recives a message to say the the controls has not been filled in correctly.
 - form validation helps in reducing the work the server do.
 - enables useres to see if theres problems with the form 

 - Data input: `<input>` a way to gather information and recognize input.
 - `type ="data"`when user gives data ,this will creat data input in the browser.

 - Emails and URLs:HTML5 allowes users to enter e-mail adrees and urls.
 - if we ask a user for email we use `type="email" ` and HTML% will validate if user entered right information
 
 - Search input: `type="search"` we use it to creat a single text box,for search query.

## Chapter 14: Lists tables and Forms.

- ` list-style-type` it allows you to control the shape of bullet point, it can be use with `<ol> <ul> <li>` elements.
- it uses (noun, disc, circle , square) in an unlorder list 
- it uses numbers and decimal leading zero and letters ,and roman.
- we can use images to act as bullets point using `list-style-image`
- list style position can either be outside bullets or inside.
- list style allows you to express the markers style .

-Table proparities:
 - width to set width of table 
 - Padding, the border between each table bordercell and the content.
 - text- transform to convert the content of table header to upper case
 - letter spacing and font size add styling to header content.
 - border top. border buttom to set borders above and below table borders.
 - background color it changes color when alternating rows.
 - :hover to hilght a table when mouse hovers over it.
 - styling a table inclues:cell padding, Distinguish heading, shade alternatRows, align numerals
 - if we have empty cells when can control how the borders will show.
 - if we want to control borders of an empty cell we can use (show,hide,inherit ) proparities.
 - we can use `border-spacing` proparty to control the spacing between cells.its spacified in pixels.
 - collapse borders are collapsed into a single border.
 - separte borders are detached from each other.
 - the more attriactive the form is the more esier users can fill it , we can change `Style text input` using 
   diffrent proparites like font size and colors . we also can change how submit button appers usiing proparites like color text-shadow hover,
   we also can style field and legend that are use dto indicate what information requierd in the field set.
 - cursor proparity allows to cintrol the mouse display to users . like set it to look like a hnad or arrow, text or wait or help.

- Web developer Toolbar
   this extension helps to show the CSS styles that applay to elements when hover over it.


 ## chapter 6 Events (JS Duckett Book).
  - there are diffrent event types, events can be useed to trigger a function.
  - here are diffrenet type of events and thier description
  
 ![Events and Description ](201/read090.jpg)

  - Events fire or raised , it happens when event has accure.
  - Event trigger script , events are triggered when the click event fires on an element.
- How events triggerJavaScript Code:
  we use event handling that takes these steps :
  1. select the element node you want the script to respond to.
  2. Indicate which event on selected node will trigger the respond.
  3. state code you want to run when the event occure.
- there are 3 types of event handler :
1. HTML handling is an old method and also abad practise because Java Script should be separated from HTML.
2. DOM handling they are better than the previous method , java sript and html are separated and its supported in all major browseres 
3. DOM level2 Event listeners it allows one event to trigger multiple functions.


## Event flow :
 in HTMl elments are nested inside other elments so whe we hover over one we also hover on its paretnt element.
 - Event bubling : the event starts at the mose spacific node and floes outword the last one.
 -Event capturing : event starts at the last node and flows inwards to the most spacific one
- flow matters when code has event handlers on element or one of its ancestor.
- when event occurs the event object tells you information abput the event and its element.

## Event deligation : 
 - when user intracts with alot of elments on a webpage, adding event listners to each of these elements can cause
    the performance to slow down , in this case we can place event handlers on containing elements and use `event object targer ` proparity.
    in order to find which of its children the event will happen on.
- there are benifits of event delgation:
   1. works with new elements 
   2. solve limitaions with `this` keyword.
   3.It simplifies your code.
- where events occur?
  the **event** can tell us where the cursor was positioned when an event was triggered.






