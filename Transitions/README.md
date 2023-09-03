# Transition

- Transforms change or move the appearance of an element while transitions make the elements smoothly and gradually change from one state to another.
- When creating a Transition in CSS, you need two properties; a transition property and a transition duration.
- To move an element from one state to another, a trigger is required. Example "hover", "has", "visited" etc.
- To have a round-trip effect of the animation on an element (to move and return back to original state animated), the placement of the transition properties is important. The transition properties should be placed in the element itself and not on the trigger.

# Transition Duration

- The dutration property specifies the time-span of the transition in either milliseconds(ms) or seconds (s).


# Transition Timing

- Transition timing function allows you to determine the speed of the transition of the duration.
- The default timing is "ease". It starts slow, speeds up then slows down at the end.
- Other timing functions include: linear, ease-in, ease-out and ease-in-out.
- Linear: Maintains the same speed all through the duration.
- Ease-in: Starts slow then speeds up and maintains the same speed for the rest of the duration.
- Ease-out: Starts at the uniform rate of speed then slows down as it approaches the final destination.
- Cubic-bezier timing function allows you to define/customize your own timing function.
- Generate, preview and copy cubic-bezier timing functions at [Cubic-bezier website](https://www.cubic-bezier.com).

# Transition Delay

- This property allows you to specify when the transform will commence.
- By default, the transition starts as soon as it is triggered. in some cases you might not necessarily want that.
- It is possible to use negative values for transition delays.


# Transition shorthand
- Instead of writing all transition properties uniquely, you can consolidate all 4 properties in one line of code like so:
- - transition: [property] [duration] [timing-function] [delay]