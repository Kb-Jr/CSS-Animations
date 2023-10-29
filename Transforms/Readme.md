# CSS 2D Transforms
- With CSS transforms we can change an element from one state to another
- With Transform we can Scale, rotate, skew, translate, transform origin of elements 
- It can be triggered when an object changes state like on a hover or a click
- Pretty much all modern browsers support 2D transforms.


## Scale
- Scale transform allows to increase or decrease the size of an element
- You can specify the specifications for each property of the object being scaled by parsing them in as comma separated arguments, example "transform: scale(width, height)"
- Add a transition property to the parent selector not the trigger to achieve a smooth and gradual transformation rather than an abrupt one.

## Rotate
- With rotate you can rotate an element clockwise or counter clockwise with a specified number of degrees
- To achieve multiple rotations multiply 360 degrees by the number of times you want the rotation to happen. Example to rotate twice, use 720deg.
- Using negative degrees will make the element rotate counter clockwise
- You can also use the keyword "turn" to specify the number of rotations

## Translate
- Translate moves an element up, down, left, right based on parameters assigned to the horizontal axis(x) and the vertical axis (y)
- syntax is as follows: transform: translate(+/- value for x axis, +/- value for y axis). Positive values moves the element to the right and downwards while negative values moves the element to the left and upwards

## Skew
- You can tilt an element to one direction or another based on the values assigned to the x and y axis
- "skewX" tilts the element in the left or right direction. A positive value in degrees tilts the element to the left and a negative x value tilts the element to the right.
- "skewY" tilts the element in the up or down direction. A positive value in degrees tilts the element down and a negative value tilts the element upwards.
- You can use shorthand of "skew" and include the x and y values as arguments like so: skew(xdeg, ydeg);
- Skewing an element also skews the child elements. To ensure the child element doesn't skew, specify the opposite of the direction the parent is being skewed to on the child element.

## Transform Origin
- Transform Origin specifies the location origin of the Transform
- By default the origin/centrepoint of every element is in the middle. 
- You can use key word values to specify the origin. Keywords such as Bottom, centre, right, top, left.
- Key words can be combined simply by typing both keywords separated by a space.
- You can also specify the origin by using percentages. Where absolute right and bottom positions are represented by 0% respectively and absolute left and top positions are represented by 100% respectively. 
- A combination of origins in percentages are represented below 
[right bottom - 0% 0%
 right top - 0% 100%
 left bottom - 100% 0%
 left top - 100% 100%
 centre - 50% 50%]
- Adjusting the values above can aid in specifying more accurately where you want your trasform origin to be.

## Multiple Transforms
- You can transform multiple properties of an element by either listing them all out individually or by using shorthand notation and seperating each property by a space
- The last property specified is usually the first property executed when the trigger event fires.

## Matrix
- The CSS matrix allows for the transformation of the Scale, Skew and Translate property in one single line.
- It does so using a co-ordinate system.
- The default method of writing CSS matrix is; Transform: matrix (1,0,0,1,0,0), each figure here represents (scaleX, skewY, skewX, scaleY, translateX, translateY)
- Changing the value of any one of these parameters directly applies the animation to the selected element. No measurement unit is required.