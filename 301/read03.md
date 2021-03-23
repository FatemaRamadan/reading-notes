## Javascript Templating Language and Engine— Mustache.js with Node and Express.
## Javascript Templating , it’s a way to render the client-side view template with JS using JSON data source . template is in HTML markup with added tags and might insert variable or run programming logic.
##Mustach , it’s a logic-less template .used in HTML,connfig file or source code. Its used by expanding tags in template.it has no *if-statement, clauses or loops*  .
-	Its considered the base for JS templating .
-	It doesn’t need separate templating system on server side .
-	Its **NOT** a templating engine, but a specification for templating language.
![log-lix templates]( https://miro.medium.com/max/700/1*P9q0tkeaRY2l1JOXaVKAig.png)
### Mustache –Express:
-	To install it with yarn
>$ yarn add mustache-express
       - to Install it with NPM:
>$ npm install mustache –save 
Then we configure it in our  server.js/app.js/index.js:
![configure Mustache]( https://miro.medium.com/max/700/1*ES10lxr7tdRFVEKcRAgLEw.png)
##A guide to flex box
-	Flexbox aims to provide an efficient way to layout align and distribute space among a container.
-	It gives the container the ability to alter items width and height to fill available space or shrink to avoid overflow.
-	It has a flex container and flex items 
-	If we have regular layout is based on both blocks and inline flow direction .
![flexlayout]( https://css-tricks.com/wp-content/uploads/2018/11/00-basic-terminology.svg)
-	Items will layout :
-**main axis** which Is the primary axis 
- **Main start |main-end** the flex items ae placed within the container.
-**main-size** which is the flex item width or height .
-**cross axis** which are The axis perpendicular to the main axis.
-**cross start| cross end** where flex lines are filled with items placed in the container starting on the cross-start side of flex container and going toward cross end.
-**cross size**the width and height  of a flex item .

Flex property’s:
-	Display ,which defines the container inline or block 
>display: flex;
     - flex direction, it defines the main-axis and the direction where elements are placed in the container.
![direction]( https://css-tricks.com/wp-content/uploads/2018/10/flex-direction.svg)
-	Flex wrap,bydefult items will try to appear on one line ,we can use this proparity to wrap them :
>flex-wrap: nowrap|wrap|wrap-reverse.
     - flex-flow, it defines the main  container and cross  axis. The defult value is no-wrap.
     - justify content 
    ![justify]( https://css-tricks.com/wp-content/uploads/2018/10/justify-content.svg)

