# Analyze-OBJ-File
Select a ".obj" file and return relevant geometric properties.

A ".obj" file is one way to represent a 3d object - it has all the relevant information needed for 3d computing programs to 
generate a 3d model including xyz corrdinates of every vertex, the vertex normals, and which three vertices form a face.
This program takes an OBJ file and returns relevant geometric features about the model such as the surface area, the volume,
and whether there are any holes in the object.  It is quite useful for our 3d printing company to know this information by simply
loading a file from a client without needing to ask them for the information, or try to first load the model onto another program.

"pathName" variable is simply changed in source code since this was for personal use and I always used the same folder.  To test it yourself, simply change this variable in line 19.
