# SMM - Stylized Grass
**Author**: SirMishMash  
The following documentation will expand upong the SMM - Stylized Grass asset.

<img src = "https://github.com/SirMishMash/Unity-StylizedGrass/blob/main/Git_docImages/Grass2.gif" />  

## Required project settings  
In order to successfully implement SMM - Stylized Grass asset into your project, please make sure your project works with the **High Definition Render Pipline (2019.4.7+)** or HDRP for short.

# Step 1: Breakdown
After adding the asset to the your project, you will find a couple files and folders. <br>
<img src = "https://github.com/SirMishMash/Unity-StylizedGrass/blob/main/Git_docImages/Breakdown1.JPG" /> <br>
The following folders are organized in a way that will help streamline your understanding for both the asset and VFX Graph in Unity HDRP. <br>

### Demo <br>
- A folder that contains files that help set up the scene "Demo - Grass" <br>
### Prefabs <br>
- A folder that contains example prefabs that you can use and experiment with <br>
### Textures <br>
- A folder that contains textures that affect how the grass is rendered and moves <br>
### VFX Graph <br>
- A folder that contains VFX Graphs that affect how the grass is spawned <br>
### Grass Profile <br>
- A diffusion profile used in HDRP that is used with the VFX Graphs provided to help create subsurface scattering effects
- **NOTE:** in order to successfully implement the profile, you must include the profile inside of the "Diffusion Profile List" in your HDRP settings.

 <img src = "https://github.com/SirMishMash/Unity-StylizedGrass/blob/main/Git_docImages/Breakdown2.jpg" /> 

# Step 2: Getting Started

Inside the Stlyized Grass folder, enter the "Demo" folder and select the "Demo - Grass" scene.
<img src = "https://github.com/SirMishMash/Unity-StylizedGrass/blob/main/Git_docImages/GetStarted1.gif" />  

The following scene will look like the following image below:
<img src = "https://github.com/SirMishMash/Unity-StylizedGrass/blob/main/Git_docImages/GetStarted2.gif" />  

By using the scene, users are given a scene where they can tinker with the asset and prefabs found with the asset package. 

Looking into the prefab folder, the user will encounter a number of prefabs with a particular naming convention. 
<img src = "https://github.com/SirMishMash/Unity-StylizedGrass/blob/main/Git_docImages/GetStarted3.JPG" />

### ex. nQuad-Circle

Section | Description
------------ | -------------
**n** or **s** | Determines what kind of particle is spawned. If **normal (n)**, the particle will spawn in normally. If **soft (s)**, the particle that spawns in will be a soft particle. A soft particle has an alpha blending effect towards object that clip into the asset creating.
**Quad** or **Tri** | Determines if the particles are spawned as **quads** or **triangles**.
**Circle** or **Plane** | Determines the shape of the particles **spawning area**. <br>**Circle**: the area the particles are spawn in are within a circle <br>**Plane**: the area the particles are spawn in are within a plane

  


**Wanna Support Me?**: http://paypal.me/sirmishmash
