# CG-PROJECT
In our childhood, we were always fond and excited to play what we commonly refer to as “Catch the ball game.” where the main task is that the ball should not fall on the ground. With our project, we aim to create a similar game simulation using OPENGL that is Catch the ball game using OPENGL.
Some functions used:
glPointSize specifies the rasterized diameter of points.
 glMatrixMode(GL_PROJECTION);  
Specifies which matrix stack is the target for subsequent matrix operations. Three values are accepted: GL_MODELVIEW , GL_PROJECTION , and GL_TEXTURE .
glLoadIdentity(); glLoadIdentity replaces the current matrix with the identity matrix
gluOrtho2D — define a 2D orthographic projection matrix. C Specification. void gluOrtho2D(, GLdouble left ,. GLdouble right ,. GLdouble bottom ,. GLdouble top )
glBegin accepts a single argument that specifies which of ten ways the vertices are interpreted. Taking n as an integer count starting at one, and N as the total number of vertices specified, the interpretations are as follows: GL_POINTS Treats each vertex as a single point. Vertex n defines point n.
The function glVertex2f specifies the x and y coordinates of the vertex, and the z coordinate is set to zero. There is also a function glVertex3f that specifies all three coordinates. The "2" or "3" in the name tells how many parameters are passed to the function.
void glVertex2i( GLint x, GLint y ). glFlush() - tells OpenGL to draw primitives now

