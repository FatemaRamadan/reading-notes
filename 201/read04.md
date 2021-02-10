## Links 
- creating a link using <a> element.
    ![Link](201/read4.jpg)
-linking to other sites using the `href` attribute.
- *absolt* URl is when the value of the href attribte is a link.it starts
with the dmian name folowed by the path.
- linking to other pages on the same website using the `relative path`.
## Directory structure
- the top level of folder is *root* it contains all the file and folder to website.
- relationships between folders and other folders are like family tree.like parent,child.grandcild
- Home page is the a site writtn in HTML and usually its called inedx.html. normally web sie set up to return index.html
- every page and image has a url; its made of domain nam followed by the path to that page or image.
- relative urls can be used when linking to pages on your website.
- Email links; to creat a link that starts email program we use `<a href = Mailto:Emailaddress>`.
- opening links in a new window using `target` on the opeing `<a>` tag and the value attribute should be `_blank`
- linkng to a spacific part of the same page:
 * you need to identify the point of the page that the link will go to using the ID arttribte
 * using the `<a>` and the value of of the `href` starts with # symbol.followed by value of the id attribute we want to link.
- linking to a spacific part of another page whether on your site or another website ; same as befor most important it has an ID.


## Chapter 15 Layout
-Positioning Elements 
- Block-level boxes start on a new line and act as the main building blocks
  of any layout
- inline boxes (flow between surrounding text).
- You can control how much space each box takes up by setting the width of the
   boxes (and sometimes the height, too).
- To separate boxes, you can use borders, margins, padding, and background colors.
- If one block-level element sits inside another block-level element then the outer box is
     known as the containing or parent element
- The containing element is always the direct parent of that element.
- controling the position of elments.css has the following positionins schems:
  1. Normal flow:every block level element appers on a new raw.
  2. Relative positioning :this moves an element from position and shift it.
  3. Absolute positionning: it position the elemnt in relation to its containng elment.
- to indicate where the box should be we use `box offset` proparites to tell the browser how far from buttom top left and right the box should be.
- we have Fixed positioning and floating positioing 
- when we miove any element from normal flow ,boxs can overlap thats whhy we use the `z-index` to decide which box appers on top.

## Chapter 3 Functions Objects and methods.
- function; lets you group a series of statment to do a spacific task
- we can reuse the function whenevr we need.
- *calling a function* , is when you want the function to do something.
- *Parameters* are pieces of informations that is passed  to the function in order to work.
- *Return Value* is when you call the function and it returns a piece of information.
- to creat a function:
1. we declare it using `function`key word
2. we give it a name.
3. then write the statments thats are needed to achice the task in the `{}`
         ![function declration](201/read 004.jpg)
- to call the function we write its name with parentheses. and a semi colon.
- when we declare the function we give it its parameters inside the function.
- Calling a function that needs information;using arguments and values.
- `return` keyword is used to return a value to the code that called the function.
- Functions can return more than one value using an array.
- Expressions produce a value. They can be used where values are expected.
  If a function is placed where a browser expects to see an expression,
  then it gets treated as an expression.
- *iffy*  functions that are not given a name. Instead, they are executed once as the interpreter comes across them
- Variable scoop ; the location where we declare a variable will affect when it can be used .
- When a variable is created inside a function using the var keyword, it can only be used in that function.
   It is called a local variable or function-level variable. It is said to have local scope or function-level scope.
- If you create a variable outside of a function, then it can be used anywhere within the script. It is called a
   global variable and has global scope
- Global variables use more memory. The browser has to remember them
   for as long as the web page using them is loaded
- Local variables are only
   remembered during the period of time that a function is being executed.

## 6 reasons for pair programming 
- pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together. 
- pair programming commonly involves two roles: 
   1.the Driver : The Driver is the programmer who is typing and the only one whose hands are on the keyboard.
   2. the navigator :uses their words to guide the Driver but does not provide any direct input to the computer.
-the 6 reasons are :
 1. Greater efficiency;it is easier to catch mistakes in the making.
 2. Engaged collaboration;When two programmers focus on the same code, the experience is more engaging and both programmers are more focused.
 3. Learning from fellow students;orking with a teammate can expose developers to techniques they otherwise would not have thought of.
 4. Social skills;improves programming skills, but can also help programmers develop their interpersonal skills.
 5. Job interview readiness;companies can get a better feel for how an applicant will fit into the team and their collaboration style.
 6. Work environment readiness.
 