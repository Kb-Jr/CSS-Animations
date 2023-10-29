# 3D Transforms

## Intro
- Working on a 2D web space, elements are usually moved around in the X and Y axis. In the 3D space and additional axis, the Z axis, is added
- The Z axis gives the element a perception of depth. It makes the element move either towards or away from the viewer.
- Negative values on the X axis, move the element to the left, while positive values move it to the right. Negative values on the Y axis moves the element upwards while positive values moves it downwards. A negative value on the Z axis moves the element away from you while a positive value on the Z axis moves the element towards you.
- We use the same Transform functions as in 2D animations, but and extra Z or 3D dimension is added. Example: TranslateZ/3d, ScaleZ/3d, RotateZ as well as Perspective and Matrix 3d.
- The Matrix 3D takes 16 values 