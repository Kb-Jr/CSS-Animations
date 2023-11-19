# Animations
- Animations comes into play when multiple states needs to be maintained or controlled (A situation where using Translate alone wiull not suffice)
- Animations consist of two components; A style describing the animation and a set of keyframes indicating the start and end states of the animation as well as intermediate points
- Keyfarmes define the stages which the animation is used
- Animation properties assigns the @keyframes to specific CSS element and define how it is animated 

## Keyframes
- Keyframes define the stages and styles of the animation
- Keyframes are defined by stating the "@keyframes" rule and its followed by an identifier. This identifier can be named at the discretion of the developer and it what is used to invoke the animation on the CSS element. within this keyframe block the "from" and "to" rules are specified as well as other intermediate states as the need arises.

- Animations can include a duration, timing function, delay, iteration count, direction and fill mode

## Animation Timing function
- Previously we've touched on using timing functions like ease, ease in out etc, another timing function that can be used is the steps function.
- The steps function can be applied when trying to achieve a more realistic movement as opposed to the smooth movements attained when using ease. For example the movement of the hands of a clock. 

## Animation Delay
- It defines when the animation will start. It allows the animation to begin execution some time after it is applied or triggered.
- Specifying animation duration is important
- The delay can take a negative value which will mean the animation executes instantaneously. It appears to start part-way through its play cycle.

## Animation Iteration Count and direction
- Iteration count Specifies the number of times the animation plays before it stops.
- Animation direction specifies if the animation should play in reverse on some or all cycles or iterations.
- The animation direction takes the following rules; Normal, reverse, alternate, alternate-reverse.
- Alternate plays the odd count of the iteration in the normal direction and the even count in the reverse direction. Reverse alternate does the opposite.
- When animations are played in reverse, the timing function will also be in reverse. So ease in will be an ease-out on reverse.

## Animation fill Mode
- Defines what values are applied to an animation outside of the time it is executing.
- Using an animation fill mode of forwards ensures that the final state of the animation execution remains even after the animation cycle. Using Backwards reverses it to its initial state.
