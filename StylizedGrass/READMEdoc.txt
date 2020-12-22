The following documentation is a brief overview about how to use the following SMM – Stylized Grass asset. 
For a more detailed and up-to date documentation please click on the link of the store asset page or follow 
the link at https://github.com/SirMishMash/Unity-StylizedGrass.
NOTE: The following asset uses Unity's VFX graph and only works in projects in 
High Definition Render Pipeline (2019.4.7+).

Import Package
 
After importing the asset into your project, you will be greeted with the following folders and files:

Demo		A folder that contains files related to how the Demo Scene
Prefabs		A folder that contains example prefabs that you can use and experiment with
Textures	A folder that contains textures that affect how the grass is rendered and moves
VFX Graphs	A folder that contains VFX Graphs that affect how the grass is spawned.
Grass Profile	A file that is used with the VFX Graphs provided to help create subsurface scattering effects. 


Demo Scene
 
When opening the Demo folder, you will be greeted by 4 different files.

Demo – Grass			A scene that is provided to show the scalability and functionality of the asset in action.
Demo Post Process Settings	A file that expands upon the scene’s post processing settings.
Demo Sky and Fog Settings	A file that deals with the sky and fog options in the scene.
Plane Mat			A material that is applied to the large plane that makes up the scene.


Prefabs
 
When opening the Prefab folder, you will be greeted by a couple prefabs for you to experiment with. 
Differences between each prefab can range from the particle type used to spawn in each blade of grass, 
whether or not the particle is a soft particle or the shape/area that the grass spawns in.

nQuad-Circle

n or s			Determines what kind of particle is spawned. If normal (n), the particle will spawn in normally. 
			If soft (s), the particle that spawns in will be a soft particle. A soft particle has an alpha 
			blending effect towards object that clip into the asset creating.
Quad or Tri		Determines if the particles are spawned as quads or triangles.
Circle or Plane		Determines the shape of the particles spawning area. 
			Circle: the area the particles are spawn in are within a circle
			Plane: 	the area the particles are spawn in are within a plane


Textures
 
When opening the Textures folder, you will be greeted by 3 different textures.

grassblade - tris	A texture with an alpha channel that will be used to render tri particle grass.
grassblade		A texture with an alpha channel that will be used to render quad particle grass. 
Noise			A texture that is used to create the wind swaying effect.


VFX Graphs
 
When opening the VFX Graphs folder, you will be greeted by 2 different folders: Grass and Soft Grass. 
The Grass folder possesses graphs that spawns the grass blades as normal particles. Whereas the Soft Grass folder 
spawns in soft particles for grass blades. 
 
Depending on the folder that you choose, you will then see VFX Graphs available to use. Each of the graphs 
offer different ways to spawn in grass. The first word determines whether or not you choose to spawn the 
particles as a quad or a triangle. The second word determines the shape of the area you want the particles to spawn in. 

Regarding what occurs inside each of the graphs, please refer to the in-graph documentation that is found in 
yellow boxes or the tooltips found in each of the nodes. 
