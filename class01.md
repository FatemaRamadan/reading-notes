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
    
    
     ### **meta data** e
     - the Meta element lives inside the `<head>` element and contains information about that web page.
     - It is not visible to users, but its needed to search engines .
     - The most common attributes are the name and content attributes, which tend to be used together. 
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
  



