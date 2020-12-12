# Git - Stylized Grass
**Author**: SirMishMash  
**Support Me**: http://paypal.me/sirmishmash

Required project settings:  
In order to successfully implement the Stylized Grass asset onto your project, please make sure your project is in HDRP.

Step 1: Getting Started
When the asset is successfully added to the your project you will find a couple files and folders. 

<img src="https://github.com/SirMishMash/Unity-StylizedGrass/blob/main/Git_docImages/Starting1.PNG">

Folders:
- grassGraphs      Folder of VFX graphs that deal with the spawning of grass blade particles and settings
- grassPrefabs     Folder of prefabs that use the VFX graphs and have altered settings. Great way to see the VFX graph setttings in action
- grassTextures    Folder of textures that are used by the VFX graph to help give shape to the grass spawned and applies the wind effect on the grass as a whole.

Files:
- Grass Profile                   A diffusion profile that deals with subsurface settings of the grass. Make sure you add this profile to your HDRP settings. (Will be expanded upon later)
- Grass Test                      A test scene where you can try out the grass asset yourself.
- Plane Mat                       A simple material that is applied on the plane used in "Grass Test."
- Sky and Fog Settings Profile    HDRP settings that deal with Sky and Fog.
