## Charts
 - they are better in visuall displaying and are easier to understand.
 - ccharts.js is  the best way to create a table is with.its a plugin that uses HTML 5 Canvas to draw the      graph into the page
- in order to creat charts:- 
  1. Download charts.js 
  2. Copy the charts.min.js out of unzipped folder and into our directory.
  3. Creat new HTML Page and import script .
- To draw a line Chart :-
*  create a canvas element in our HTML and add
`< canvas id="buyers">` `< / canvas >`
* Get context and instantiate the chart.
* create the data by supplying a value and a color for each section.
* Then we add our options.
* Finally, to add a bar chart:- we add the canvas element ,then we retrieve the element and creat the graph then we add the bar charts data.



## Basic usage of canvas 
- '< Canvas >' has 2 attributes  ' width ' and ' hight '. They are optional but better to use them .
- I ts  always a good idea to add ' id ' to make it easier to identify it  in the script
- ' < canvas> ' can be styled like a normal image.
- we need to provide  fallback content by inserting them in the canvas tag and add .a closing tag.IIn browsers that don't support '< canvas> ' they will ignore the content and render canvas normally..
- canvas element creat a fixed size drowing that shows one or more * rendaning context* 
- rendaring context is used . to creat and manipulate the content.
- In order to display the content : first we need to access the rendaring context and drow on it .
- the ' getcontextc() ' is used to obtain rendaring context and it's drowing functions. it also takes one parameter which is type of context.
- scripts can check for support programmatically by testing the presence of ' get Context() ' method.


## Drawing shapes with canvas
- usually 1 unit in the grid = I pixel on the canvas. 
- the grid is positionat in the top left corner at coordinate ( O , O ) 
drawing a rectangle:
we use 3 functions 
1 . ' fill React(x , y , width , hight ) this function drows a filled rectangle.
2. strokeRect ( x, y , width , height ) this draws a rectangular outline.
3. clearRect (x , y , Width , height ) this clear the spacified rectangular area and make it transpernt. .



- Drawing paths
- path is a list of points connected by segments of lines
1. ' begin path()'  To creat the path
2. then we use drowing commands to draw into the path.by calling the methods that spacify the path to drow.
3. Once the path has been created we can stroke or fill the path to render it, by using ' close path () ' 


## applying styles and colors.
- we can apply 2 proparites : ' fillStyle= ' color' ' is used When filling shapes
and ' strokeStyle= color '  .it sets the style for shapes out line
- transparency: we can achive that by either: ' global Alpha ' and setting it to trancperacyValue.or by assinging a semi - transparant color to stroke or fill style.
- Line styles :
 value | | proparites
 ---- | | ----
`LinewidthValue`  | |  the width of line drown in the future.
`lineCap` | | sets the appearance of the and of lines
`lineJoin`| |  set the appearance of the corners where lines meet.
`miterLimit=Value` | | establishe a limit on the miter When two lines Join at a sharp angle.
`getLineDash()|| establish a limit on miter when two line join at a sharp angle.
`setLineDash(segmants)|| sets the  current line dash pattern
`lineDashOffset=value`||spacifies where to start a dash array on a line.

- Patterns , we can creat patterns by using `creatPattern(image,type)` :
  * `img` is like a normal html element that has a source 
  * `type` it spacifies how to use image in order to creat the pattern it must be one 
     of these (`repeat` ,`repeat-x`,`repeat-y`,`no-repeat`)
- Shadows it has 4 proparites : 
 1. `shadowOffsetX=float`  its for the horizantal distance the shadow should extend from obj.
 2.`shadowOggsetY= float` for the vertical distance the shadw should extend from
 3.`shadowBlur=float` for the size of the blurring effect.
 4. `shadowColor = color`  its for setting the color of the shadow.
- Canvas fill rulee , when we use `fill` or `clip` we provide a fill rule algorithm that checks if a point is indide or outside a pth and so it eaither gets filled or not.
  it has 2 possible values:
   - `nonzero` and `evenodd`

## Drawing texts 
- there are two methods to render a text :
   1. `fillText(text,x,y[,maxWidth])` that fills the text of (x,y) position 
   2. `strokeText(text,x,y[,maxWidth])` stroked a given text of (x,y) position.
- styling text:
   proparity || description
   ------||------
   `font=value`|| the text style that is used to draw a text
   `textAlign = value`|| its either left,right,end,start or center.
   `textBaseline= value`||for basline alighnment it has values of(` top`, `hanging`, `middle`, `alphabetic`, `ideographic`, `bottom`)
   `direction -value`|| directionallity it has vakues such(`ltr`, `rtl`, `inherit`)
- If we want more details of text we can use `mesureText() that would allow us to mesure it
