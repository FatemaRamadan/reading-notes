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
- when we move any element from normal flow ,boxs can overlap thats why we use the `z-index` to decide which box appers on top.
- `float` proparity :The float property allows youto take an element in normal  flow and place it as far to the left or right of the containing element as possible.
- A lot of layouts place boxes next to each other. The float
property is commonly used to achieve this.
- `clear` :the clear property allows you to say that no element (within
the same containing element) should touch the left or righthand sides of a box. It can take the following values:
 * left;he left-hand side of the box should not touch any other     elements appearing in the same containing element
 * right;The right-hand side of the box will not touch elements appearing in the same containing element
 * both;Neither the left nor right-hand sides of the box will touch elements appearing in the same containing element.
 * noun ;Elements can touch either side.
- If a containing element only contains floated elements, some
browsers will treat it as if it is zero pixels tall.
 - to fix this problem :
 add two CSS rules to the containing element :
 1. The overflow property is given a value auto
 2. The width property is set to 100%.

- creating multiple colomns in layout with float:
This is achieved by using a `<div>` element to represent each column
the next proparites shows how colomun are next to each other:
1. width
2. float
3. margin


### Screen Sizes 
- who are viewing the site have diffrent screen sizes so the designe should be combatable with these devices.
- Screen Resolution ;Resolution refers to the number of dots a screen shows per inch.
- Page sizes ;Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide.
- Fixed width layout Fixed width layout designs do not change size as the user increases or decreases the size of their browser window.
Measurements tend to be given in pixels.
![advantges and Disatvantges of Fixed width layout](201/read077.jpg)

- Liquid Layouts;Liquid layout designs stretch and contractas the user increasesor decreases the size of their browserwindow. They tend to use percentages.
![Advantges Vs. Disadvantges of liquid layout](201/read0777.jpg)
- Summary :
- Designers keep pages within 960-1000 pixels wide,and indicate what the site is about within the top 600
- pixels (to demonstrate its relevance without scrolling).
- X Grids help create professional and flexible designs.
- X CSS Frameworks provide rules for common tasks.
- X You can include multiple CSS files in one page


