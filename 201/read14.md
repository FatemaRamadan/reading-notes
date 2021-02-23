
## What Google Learned From Its Quest to Build the Perfect Team
Google created project  Aristol in order to figure out the secret recipe for the  perfect successful teams.
using the people in Google as a search groups . they started to look for patterns in different groups
and looking for similarities , but the problem was there where no common patterns and so .one of the searchers suggest 
using "group norms"; its traditions and behavioral standards and unwritten rules that controls how we function when we are together.
people may behave differently as induvial, but in the groups `norm ` it overrides individualism and encourage deference to the team.
the conclusions was understanding and influencing the group norms were keys to improve Googles teams.
researcher’s wanted to know if there a collective I.Q that emerge within a team the is distinct from the smarts of any single member and so
they made had a group of 699 people and divided them , they gave them a set of tasks that require team cooperation.
the observation that researches came to is that if team failed first task they will probably do the same in the second one ,vice versa.
and the key of that result was how team members treated each other. But again not all teams appeared to behave the same.
researchers found two behaviors that were common in good teams:
- first was that members spoke in the same proportion and took turns in leadership.
- the second one was that all team members had average social sensitivity.
this is also reoffered to as psychological safety .
Aristol searchers pointed particular norms of success regarding psychological safety.
which is important for teams to success among other factors such as having clear goals and creating a cultural dependability.
However the teams at Google had a problem in applying this method because most of them became Software Engineering b because they don’t want to talk about their feelings.
so after a while when applying psychological safety and allowing team mates to participate and sense others feelings it helped a lot with the success of this team .
Google found a way using Aristol experiment to make Its employee think of works as part of their lives, they don’t have to be separated people while at work.

## transforms
- general laout techniques can be revisited with alternative ways to size position ..
- we can applay these techniques by the `transofrm` property.
- it comes with 2D and 3D each one has its own proparites and values.
 
- transform context 
- first we include the transform proparity followed by the value followed by the spacific amount inside ()
- the transform proparity include multiple prefixes to be supported by all browsers.

- 2D transform :
-the 2D transforms works in the X and Y axes, while 3D works on X,Y and Z .
- `transform:rotate();` provides the ability to rotate an element. the positive values rotates clockwise while the negative value 
  rotates counterwise.the default is center of the element.

- 2D scale:
- it allow us to change the appeared szie of an element.
- default scal is 1 values <1 will appear smaller while >1 will appear larger.
- `scaleX, scalY` are used to set the hight or width of an element.

- 2D translate:
- `translate` value its similiar to positioning , pushing and pulling element in diffrent directions without inuterrupting the normal flow of the document.

- 2D Skew
- its used to distort element on the hoizantal axis.vertical axis 
- ` transform:skewX()`
- combining transforms  is very common we can use the rotate+scale over an element.

transform origin 
- the default tranform origin is the dead center of an element .
- to change this default origin we use `tranform-origin` . it accepts one ot 2 values .
- when one value is set its used for both horizantally and vertically.

prespactive:
- we use it for 3D elements to work .
- it can be set using the `prespactive ` value inside the transform proparity on indivisual elements.
- it can be set as none or a lenght mesurments.
- we can use the origin with the prespective value.

3D transforms :
- 3D rotate : we use `rotateX, rotateY, rotateZ` .
- 3D scale : we scale it to the Z axis.
- 3D translate: to also control the size of elements.
- 3D skew it cant be used on 3D
- transform style : on occasion three-dimensioanl transform will be applied on an element within a parent element.
- backface visibility  we can use this proparity and set it to hidden in order for not letting items to show from the back.


## Transitions & Animations
- the usual transitions that we have are the psedudo- classes such as hover and focus.
- there are 4 transitions related which are `transition-property, transition-duration, transition-timing-function, and transition-delay`.
- `transition-property` determine what proparity to be alterd with other transition proparities.
- not all proparites can be transitioned.
- `transition-duration` it can be set using general timing values .
- `transition-timing-function` is used to set the speed of how transition will move.
- the liner is when a transition moving in constant speed from a state to another.
- the `ease-out` identifies a transition that starts quickly then slows down .
- the `ease-in` the transition starts slowly speeds at the middle then slows down again.
- the `transition-delay` set a value that tells  how long should the transition delayes befor it starts .
- Animation keyframs 
- we use `@keyframes` rule it includes the animation name and break points and proparities.
- we can use many values to animation such as : `animation-name:slide`, `animation-duration` and an `animation-timing-function`.
- to make animation iteration we use the `animation-iteration-count` proparoty .
- `animation-direction` is used to declare the direction for the animation.
- `animation-play-state`for allowing animation to be palyed or paused using running and paused.
- `animation-fill-mode identifies how elemnt is styled after or befor animation is styled .
 
