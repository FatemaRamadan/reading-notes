# Duckett HTML introduction
## chapter 1: Strucure

  #### HTML descripes the strucure of a web page 
   - HTML code is made up of charechters that are put inside `<>` angled brackets.
   - these are called **Elements** usually they are made of **2 tags** an opening tag and a closing tag.
   - each HTML element tells the broweser information that is between its tags

   #### HTML uses elements to describe the strucutre of pages 
     - tags act like containers.
       - `<html>` and `</html>` shows that anything between those two are HTML code.
       - `<boday>` and `</body>` shows that anything written between will apper on the HTML page.
       - `<h1>` is the main heading.
       - `<p>` shows a paregraph.

    #### attributes tells more about elements.
    - attributes provide additional information about elements.
    - each attribute has a name and a value separeated by an `=` sign.

    ### Body , Head ,Title.
    - `<boday>` is where everything on the page appears.
    - `<Head>` it conatins information about the page.
    - `<title>` is shown at the url name on the broweser.
 
## Chapter 8 : Extra markup

 #### the evolution of HTML
 - there has been many versions of HTML starting html4.
 - the HTML5 is the version that is used today.
 - `<!Doctype>` is the first tag i the page. it tells the browser which HTML version to use.
 - to Comment in HTML `<!--   -->`.

 ##### ID attribute .
 - every HTML element can carry the *id* attribute.
 - its used to **uniqully identified** an elemnt from other elements on the page.
 -  Its value should start with **a letter or an underscore**.
 - no two elements on the same page have the same value for their id attributes. 
 - The id attribute is known as **a global attribute** because it can be used on any element.

##### Class attribute .
 - its a way to identify several elements as being different from the other elements on the page.
 - The class attribute on any element can share the same value.
 
 #### block Element.
 - always appear to start on a new line in the browser window.
 - such as `<h1> <p> <ul> <li>`.

 #### Inline Element.
  - will appear on the same line as its naighbour element.
  - such as `<a>  <em> <b> <img>` .
   
   #### grouping text and elements in a block.
    - The `<div>` element allows you to group a set of elements together in one block-level box.
   
   #### grouping text and elements in a block.
    - The `<span>` element acts like an inline equivalent of the `<div> `element. It is used to either:
        1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text.
       2. Contain a number of inline elements.

  ####  IFrames
     - **iframe** is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame.
     - there are some attributes to use with Iframes like : * src hight width *.
     - **scrolling** it indicates whether the iframe should have scrollbars or not.
     - **frameborder** , it indicates whether the frame should have a border or not. A value of 0
        indicates that no border should be shown. A value of 1 indicates that a border should be shown.
     - **seamless**, seamless can be applied to an iframe where scrollbars are not desired.
    
    
     ### **meta data** 
     - the Meta element lives inside the `<head>` element and contains information about that web page.
     - It is not visible to users, but its needed to search engines .
     - The most common attributes are the name and content attributes, which are used together. 
       - description: This contains a description of the page.its commonley used in search engines.
       - keywords: This contains a list of commaseparated words that a usern might search on to find the page.
         In practice
       - robots : This indicates whether search engines should add this page to their search results or not.
       
    ### Escape charechtaristics
    - for copyrights is represented as `&copy`.
    - for trademark is represented as `&trade`.


## Chapter 17: “HTML5 Layouts".
  - traditional HTML layouts usually uses `<div>`elements to group together related elements on the page.
  - elements that form a header, an article, footer or sidebar.
  - New HTML has elements that describe the content you eill see in them .
  - Examples of new HTML layout are `<div> for header and <nav> for navigation , articles in <article>`.
  - the Header and footer appear at the top and bottom of each page.
  - the *nav* element is used to contain navigations or blocks of the page.
  - the `<articl>` is used to contain a section of the page that could stand alone.
  - the `<aside>` serves 2 purpose  based wether its in an `<article>` or not;
    - if its inside `<article>`;it should contain info. important to the article but not the overall meaning.
    - if its alone;it acts like a container that is important to the eniter page.
  - the `section` element is used to group related content and usually each section has its own heading.
  - the `<hgroup>` is used to contain set og one `<h1>` or more to be treated as one big heading.
  - the `<figure> and <figcaption>` is used to contain any contect that is refrenced from the main flow.
  - HTML5 allows web page authors to place an <a> element arounda block level element that contains child elements. 
  - to help older broweser understand HTML% we can :
    1. add css to the left to states which new elements should be rendered as block-level elements.
    2. in IE9 we need se a simple JavaScript known as the HTML5 shiv or HTML5 shim.


 ## Chapter 18: “Process and design". 
    Why visitors come to the you site ?
1. we have to discover underlaying motivation.
2. discover the spacific goal for visiting the site.
# key motivation
- are they looking for entertainment or a spacific goal? 
- if it is a spacific goal is it personal or profissional?
- do they spend time as luxury or essentiol?
# specific goals
- do they want general or specific information?
- are they familire with the service or need further details?
- are they looking for sensitve time information?
- do they want more information?
- do they need to contact you ?

# what your visitors are trying to achive ?
you have to creat a list of reasons of why people would come to site 

# after knowing who is coming to your site and why ,now we need to know the information they need or want to achive 
- offer additional information 
- look in each reason that make people come to your site then determine what they need 
- prioritize levels of information
- make sure to provide information that your audiance want .

# how often people will visit your site ?
depending on the updates you have to make 

Site Map.
creat a digram of the pages that will be used to structure the site .
this is called site map
to know what inforamtion you should put in pages use Card Sorting; 
its like putting certin information to a pices of paper 


Wireframes
its a simple sketch that shows the information needed in each page 
its important because you can ensure all the information that is needed should be included at the page.

getting your message across using design
- we have to creat content relative t the page
- prioritizing; by makeing partsof a the page look distinct 
we can do that using a visual hirarchy.
-orgnizing grouping together related content into blocks or chunks.

Visual Hirarchy 
Visual hierarchy refers to the order in which your eyes perceive what
they see. It is created by adding visual contrast between the items being
displayed. Items with higher contrast are recognized and processed first.
most web users dont read entir pages,rather they skim to information we have to pay attention to:
1. size 
2. color
3. style 


<h2>Grouping and simiarity</h2> 
to make a better design we should put related visual elements in groups.
some of this grouping styles are(proximity,cloure,white space...etc)

# THe ABC of programming 

1. what is a script and how do i creat one?
   - script is a series of insturctiond that computer has to follow to achive goal.
   - a browser may use diffrent parts of the script depending on how the user intracts with the webpage.
   - a script can run diffrent sections of codes depending the situation.
   - to write a script first you have to:
      * state your goal.
      * list tasks that you need to complet.
         * Define the goal
         * design the script (split the Goal into series of tasks)
         * code each step.


 ## designing a script:
 - after dividing tasks we can use **flow chart** .
 - each task may be divided into a **Sequance of steps**.
 - these steps then can be divided into **lines of code**.
## from steps to * Code *
 - every line in tasks needed to be written in a language the computer can understand.
 - we need to think like a computer because the achive things diffrently than humans.
 - Designing the Goal and the script:
   * detail your goal to the script (what you want to achive).
   * break tasks into aseries of orders to be performed.
## skitching the tasks in a flow chart.
 - arrows shows how the script moves from one task to another.

2. How do computers fit in the world around them?
  - Computer creates models of the world using data.
  - programmers creat modules for computers using data
##  Objects and proparites 
  - objects has :
   * proparites 
   * events 
   * methods
  - Proparites (charchtarstics) has:
   * name 
   * Value 
  - Events : how the user intract with computer
  - Methods : how people intract with objects.it contains instructions that represent one task.

  ## web browsers are programmes built using objects.
   - window object it represent an HTML page 
    * how browser sees a web page :
       1. retrive a page as HTML code 
       2. creat a module of the page and store it in the memory 
       3. us a renerd engine to show the page on the screen.
    * all major browesers use Java scripts to interprate the instructions to computer can follow.
   - document object 

3. how do i write a script for a web page?
  - HTML is the content layer 
  - CSS is a representaion layer
  - J.s is behivoral layer
- crating a javascript :
 * creat a folder with the exctension of .js
 * link it to html page using `<script>` element .
 * place the script into the page 
 * java script run whenever its found in html. 

  



