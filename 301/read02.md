## chapter 7 : JQuery
JQuery is a library that allows us to find selected elements using CSS-style selector and then perform a method to that element . it helps us with :
1.	Selecting elements , its easier in in jQuery rather than the DOM.
2.	Perform tasks , it allow us update DOM tree and animate elements .
3.	Handle events , it has methods to attach to event listener to selected elements 
The jQuery function has one parameter which is a CSS-style selector:
![Jquery function]( https://www.developerdrive.com/wp-content/uploads/2011/09/jquery-anatomy.jpg)
-	The jQuery is similar to traditional DOM queries but simpler.
-	We can store jQuery object in a variable.
-	We can use the jQuery methods and properties to manipulate the DOM.
-	In order to use jQuery we need to include the file in the `<script> ` tag.
Example on using jQuery
![jquery function]( https://player.slideplayer.com/92/15219738/slides/slide_32.jpg)
##why use JQuery:
1.	Simple selectors, its almost accurate about which element to select
2.	Common tasks in less code, such as looping through elements and adding and removing elements from DOM tree , handling events.
3.	Cross- browser compatibility, it automatically handles the different between browsers in selecting elements .
jQuery has many support code for IE6 ,7 ,8 so the code went bigger , then developer removed the code for older versions to make it simpler and more fast. 

### jQuery selections
-	** a matched set ** , is when selecting one or more element the jQuery obj. is returned .
-	It can return either, a single element or a multiple elements .
-	**get and set data** getting information using jQuery ; if the selection held more than one value jQuery takes only the first element in the matched set ,
However, Setting information if the jQuery hold more than one element and method is used to update information , it will update all the elements in the matched set.
-	When we create selection with jQuery it saves a reference for it in the DOM tree not create a copy form it .by storing the location a piece of information in browser memory 
-	Cashing jQuery object stores a reference to it in a variable in order to use the same selection more than once .
-	In jQuery there is no need to loop  if you want to apply a certain code to some elements , we can update them all using one method .
-	**chaining** , if we want to use more than one method on an element we list several methods by using dot notation.
-	`jQuery.ready()` this method check if the page is ready for the code to work with .
Example:
![jqueryready]( https://prakashdrupal.files.wordpress.com/2017/01/document-ready_.png)
-	In order to get content we use `.html()` and `.text()` methods to retrieve and update content.
-	`.html()` this method retrieve information from jQuery selection ,and only the HTML inside first element along with any of its descendants.
-	`.text()` it retrieves text from jQuery selection , it takes the content from every element in jQuery selection and it descendants .
-	**inserting Elements **  by creating the new element in jQuery obj  then use the method to insert content into page using `.before() .after() .prepend() .append() `
-	`.attr()` this method get or set a specified attribute and its value.
-	`.removeAttr()` this method removes the specified attribute and its value.
-	`.addClass() ` adds a new value to the existing value of the class attribute.
-	`.removeClass()` removes value from class .
-	`.each()` allows us to loop statements on each of the items in the selection of elements.
-	`on()` this method for handling all the events .
-	We also can applay effects such as `fadeIn() slideDown()` .

## how to include JQuery in the page?
-	We place the script tag at the end of the `<body> ` tag and it will not effect the page loading 
-	We can also replace it in the head but it can cause the load page to be slower and the DOM content is not loaded 
-	If we placed it in the middle of the page it will slow the rest of the page 



##6 reasons for pair programming 
- pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together. 
- pair programming commonly involves two roles: 
   1.the Driver : The Driver is the programmer who is typing and the only one whose hands are on the keyboard.
   2. the navigator :uses their words to guide the Driver but does not provide any direct input to the computer.
-the 6 reasons are :
 1. Greater efficiency; it is easier to catch mistakes in the making.
 2. Engaged collaboration; When two programmers focus on the same code, the experience is more engaging and both programmers are more focused.
 3. Learning from fellow students ;working with a teammate can expose developers to techniques they otherwise would not have thought of.
 4. Social skills; improves programming skills, but can also help programmers develop their interpersonal skills.
 5. Job interview readiness; companies can get a better feel for how an applicant will fit into the team and their collaboration style.
 6. Work environment readiness.
 

