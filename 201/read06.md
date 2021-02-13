## Chapter 3 : Objects Literals
- Objecsts group toghther a set of variables and functions to creat a module of something you would recognize from real world.
- In An Oject ; *Variables* become *proparities*(they tell us about the Object).
- *Functions* become as *Methods* (represent tasks that are associated with the object.
- *Key* is the Name and value for methods and proparites.
- objects cant have two *key* with the same name .
- the Value of a proparty can be anything , but Methods value is always a function.\
- When declaring an Object:
  - We put the object in curly braces .
  - Separate each key from its value using a colon.
  - separte each proparty and method with commas.
  - treat values like you would do for variables.
- We can access a properties or methods of an object using dot notation.
- we can access proparites using square brackets.
- to access proparity or method of an object we use the name fo the object followed by a period then the name of the project.
- we can also access proparties by writing the object name and put the propaiteis between square bracits.

## Chapter 5 :Document Object Module.
- The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the
  contents of a web page while it is in the browser window.
- it is a separate set of rules.It is implemented by all major browser makers, and covers two primary areas:
   1.Making a module of HTML page. using a *DOM tree*.
   2.Acessing and changing HTML page.The DOM states what your script can "ask the browser about the
   current page, and how to tell the browser.to update what is being shown to the user.
- The DOM tree is a moudle of web page it consists of 4 parts
   1. THE DOCUMENT NODE.it represent the entire page
   2. ELEMENT NODES
   3. ATTRIBUTE NODES
   4. TEXT NODES
- every node is a descendant of the document node
- Accessing and updating the DOM tree involves two steps:
   1: Locate the node that represents the element you want to work with.
     - To select an indivisual elment nod : `getElemetnById()`;`querySe1ector()`;
     - To select multiple Elements : `getElementByClassName()`;`getElementsByTagName()`;`querySelectorAll()`;
     - Traversning between Elements: `parenNode`;`previousSibl ing / nextSibl ing`;`firstChild / lastChild`;
   2: Use its text content, child elements, and attributes.
      to see how to use the content :
       
      ![DOM text content ](201/read06.jpg)

 - Cashing DOM queries.
   * Methods that find elements in the DOM tree are called queries.
   * DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.
 - *Nodelist* when a method can return more than one node, it will always return a Nodelist, which is a collection of
      nodes even if it only finds one matching element.
- Finding the quickest way to access an element within your web page will make the page seem
    faster and/or more responsive.
- Methods that select indivisual elements : `getElementById() and querySelector()`.
- Selcting an elment from a Nodelist : the `item(),`and array synatx.
- repeating actions for an entir nodelist : Loop through every node in the collection and apply the same statment to each.

## adding or removing HTML content:
- the `innerHTML `proparty 
- DOM manipulation methods 
-From an element node, you can access and update its content using properties such as textContent and
   innerHTML or using DOM manipulation techniques.
- An element node can contain multiple text nodes and child elements that are siblings of each other.
- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
- Browsers offer tools for viewing the DOM tree.
