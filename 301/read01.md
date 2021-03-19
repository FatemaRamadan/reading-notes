## What is Responsive web design ?
It’s the ability to create websites  that are convenient for display on all kind of screens and mobiles .
And providing a satisfying experience for users 
##Responsive vs. Adaptive vs. Mobile
Responsive and adaptive are very similar but also very different , responsive means > “to react quickly and positively to any change >” while adaptive means “to be easily modified for a new purpose or situation, such as change”.
A combination of adaptive and responsive is perfect to make a great website.
## Flexible Layout
This is made of 3 main components:
1.	flexible layouts, its creating a website layout with flexible grid, able to resize to any width.
These grids are built with relative unite such as percent or em , and are used to declare width , padding, margin. While the view port change from device to another , websites need to adapt this view by using relative values .its calculated by taking the target width and of an element and divide it by its parent element width. 
       `target ÷ context = result`

2.	media queries, this component is were built as an extension to media found in targeting and included styles .it has the ability to specify for individual browsers and devices circumstances.
We can use the `@media ` rules inside an existing style sheet; by importing or linking to a separate style sheet inside the html document.
Each media query can use one or many expression like : `all  ,screen , print , tv` if the media type is not specified it will use the default to `screen`.
Logical Operators in Media Queries :
-	 `and` allows an extra condition to be applied ,in order to make device or browser’s to make `a,b,c `. 
-	Example , this one selects all media types within 800 and 1024 pixels :
        `@media all and (min-width: 800px) and (max-width: 1024px) {...}`
-	The `not` operator , negates the query specifies any query but neglects the identified one 
-	The `only` only selects  screens in a portrait orientation.
-	> Omitting a Media Type
  When using the` not` and `only` logical operators the media type may be left off. In this case    the media type is defaulted to all.
-	### Media features identifies what attributes will be targeted within the media query expression.
-	Determining the `height` and `width` for any device ,they can also be prefixed by adding `min,max` qualifiers.
-	`max-width and min-width` are very helpful in building a responsive web site for different devices and also avoid confusion with these devices features .
-	The orientation media feature ; this determine If the device is landscape or portrait orientation. Landscape is triggered when display is wider than taller , while portrait is triggered when the display is taller than wider. Its most important with mobile phones .
-	The Aspect Ratio media feature ` aspect-ratio and device-aspect-ratio` specifies the width and height of the targeted area or the device. Its value consists of two positive integers separated by a `/`. The first integer specifies the width and second one specifies the height. both in pixels .
Example : ` @media all and (min-device-aspect-ratio: 16/9) {...}`
-	Pixel ratio media feature that includes `device-pixel-ratio` which is great for identifying devices with high resolution 
-	`Resolution Media Feature` ; this feature specifies the resolution using density per Inch DPI. It doesn’t accept `min`max` but it accepts dot per pixel .
-	Other media features include identifying available colors or monochrome features .
-	### Mobile first ,
![MobileFirst display ]( https://miro.medium.com/max/700/0*859VX66vAlmvVxib.jpg)
 this technique include styling for smaller viewports  as the default style for website and when the display grow we add media queries. This point of view is also allowing users not to wait for all the  style of desktop computer to download and  consume a huge bandwidth .

3.	flexible media , media like videos images and others  doesn’t changes size as view port so , we use `max-width property` with 100% value , by doing so any media gets smaller like the view port and scale to the required size .for example
 ` img, video, canvas {
-	max-width Media unfortunately doesn’t work with all types of media that have iframes , so we use `work around` , to let the media responsive ; the targeted media needs to be absolute positioned to the parent element . the parent element should have the width of 100% and height of zero in order to trigger the `has-layout `mechanism in internet explorer , then we give the parent a bottom padding 
## What is float ?
-	It’s a position property that is used in CSS , if we applied it to images text and other elements will float around it , floated elements remain a part of the flow of the web page unlike absolute positioned element were they are removed from the flow .
-	There are 4 valid values for this property which are left, right , none and inherit . 
-	We use float to design an entire web page layout 
-	![web layout]( https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/web-layout.png?resize=540%2C240&ssl=1)
-	`clear ` property will ignore the float , but will move down past the float element , it has 4 valid values : `both` is used to clear float coming from both sides ,`left & right ` is used to clear float from one side and the last one is `noun` 
-	The `float ` property also affects their parent element if it only contained floating element causing its width to collapse.
![parent Collapsed]( https://i0.wp.com/css-tricks.com/wp-content/csstricks-uploads/collapse.png?resize=540%2C182)
 In order to fix this issue we clear the float **after** the floated elements in the container but** before **the close of the container .
## techniques for clearing the float.
-	The Empty Div Method. Which is creating an empty div and then give it style `clear:both`.
-	The Overflow Method. which is setting the overflow CSS property on a parent element .
-	The Easy Clearing Method.it uses the `:after ` pseud selector to clear the float .
## problems with floats
-	**push down ** where elements inside floating item will be wider than the float it self
-	 **Double Margin Bug ** if we added  margin in the same direction of the float it doubles the margin.
-	** The 3px Jog** when we have text that is next to float it magically kicked away by 3px!
-	** Bottom Margin Bug** when floating parents has floating children .bottom margin for these children is ignored by the parent element.
