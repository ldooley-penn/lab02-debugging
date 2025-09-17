# Submission
Worked with Rebecca Waterson

https://www.shadertoy.com/view/tfsfWf

line 97: Compilation error using vec instead of vec2
- Found through compiler error
line 101: Raycast used uv instead of uv2
- Found by rendering just uvs as color and noticing they were shifted
line 11: Aspect ratio transform was using x/x instead of x/y
- Found by rendering ray directions
line 18: Iteration count was too low to see much ground
- Found by noticing effects around edges of spheres, which I knew that when ray marching could be caused by approaching tangent surfaces.
line 75: Made sure to reflect dir instead of eye about the normal
- Found by rendering the reflected direction as color
