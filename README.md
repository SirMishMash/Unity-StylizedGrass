# Git - Stylized Grass
**Author**: SirMishMash  

<img src = "https://github.com/SirMishMash/Unity-StylizedGrass/blob/main/Git_docImages/Grass1.PNG" />  

Required project settings:  
In order to successfully implement the Stylized Grass asset onto your project, please make sure your project is in HDRP.

Step 1: Getting Started
When the asset is successfully added to the your project you will find a couple files and folders. 

<img src = "https://github.com/SirMishMash/Unity-StylizedGrass/blob/main/Git_docImages/Starting1.PNG" />

Folders:
- grassGraphs      Folder of VFX graphs that deal with the spawning of grass blade particles and settings
- grassPrefabs     Folder of prefabs that use the VFX graphs and have altered settings. Great way to see the VFX graph setttings in action
- grassTextures    Folder of textures that are used by the VFX graph to help give shape to the grass spawned and applies the wind effect on the grass as a whole.

Files:
- **Grass Profile**  
  * A diffusion profile that deals with subsurface settings of the grass. Make sure you add this profile to your HDRP settings. (Will be expanded upon later)
- **Grass Test**  
  * A test scene where you can try out the grass asset yourself.
- **Plane Mat**  
  * A simple material that is applied on the plane used in "Grass Test."
- **Sky and Fog Settings Profile**  
  * HDRP settings that deal with Sky and Fog.

Step 2: Grass Test Scene  
A Unity HDRP scene that will allow you to see and experiment with the "Stylized Grass" asset. In the following image, the "Grass Test" scene is scene.  

<img src = "https://github.com/SirMishMash/Unity-StylizedGrass/blob/main/Git_docImages/Scene1.PNG" />  

Heiarchy:
- **Lighting Settings**:      An empty game object with HDRP settings placed inside  
  * **Directional Light**:
  * **Post Process Volume**:
  * **Sky and Fog Volume**:
- **Plane - Home**: The plane where the assets and character controller rest on
- **Unity Chan Controller**: A basic character controller that uses [Unity Chan](https://assetstore.unity.com/packages/3d/characters/unity-chan-model-18705) 
- **Main Camera**: Main camera used to follow Unity Chan.            
- **GrassPlane-Quads**: A plane of grass that uses quad particles 
- **GrassPlane-Tris**: A plane of grass that uses triangle particles 
- **gCircle-Quad**: A circle of quad particles
- **gPlane-Tris**: A large plane of triangle particles with altered parameters to spawn more grass on a larger surface area


**Wanna Support Me?**: http://paypal.me/sirmishmash
