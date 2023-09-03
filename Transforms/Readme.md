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
- Skewing an element also skews the child elements. To ensure the child element doesn't skew, specify the opposite of the direction the parent is being skewed to on the child element
