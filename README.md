# MeshGenerator
Generating a mesh by script inside Unity

What it is:
Following the simples tutorials from Brackeys on his channel on Youtube, this project generate mesh from script.
The current version draws a plane of user defined dimensions on the XZ plane by creating the triangles and assigning them to a mesh.
It also add noise, using linear interpolation on the Y-axi to create height. 

How it works:
Simple open the project on Unity (version 2018.3+). Navigate to the folder Scenes and open SampleScene. Select the MeshGenerator object and
set the dimension of the plane in the xSize and zSize fields of the MeshGenerator component. Hit Play and see the results.
