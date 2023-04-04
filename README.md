<h1 align="center"> Hero Cross Reality Application - Project Structure </h1>

<p align="center"> This Unity project contains several Virtual Reality trainings and includes several directories with different types of assets, such as scripts, scenes, prefabs, textures, and audio files. In this README file, we will provide an overview of each directory and describe its contents.</p>

## Table of Contents

> 1.0 [Description](#structure-DESCRIPTION)

> 1.1 [Project Structure](#structure-ProjectStructure) 

> 1.2 [Project Hierarchy](#structure-ProjectHierarchy) 

<a name="structure-PREREQUISITES">_PREREQUISITES</a>

<h3 name="#structure-DESCRIPTION">Description</h3>

- Developers :
This directory includes files and documents intended for developers working on this project. It may contain guidelines, instructions, scripts, or other resourcesto facilitate the development process.
- Documentation :
This directory contains the project's documentation, which may include user manuals, installation guides, or technical specifications.
- Oculus :
If this project is intended for use with Oculus devices, this subdirectory may contain specific documentation related to Oculus integration.
- Plugins :
This directory contains any plugins or external libraries used by the project.
- ProjectReferences : 
This directory contains subdirectories with different types of assets used in the project. 
- Art :
This subdirectory contains all of the project's art assets, such as Materials, Models, Shaders, Textures.
- Audio :
This subdirectory contains all of the project's audio assets, such as AudioClips, AudioMixers, Music.
- Prefabs :
This subdirectory contains all of the project's prefabs, which are reusable game objects that can be used to quickly add functionality to a scene.
- Scripts :
This subdirectory contains all of the project's scripts, which are used to define the game's logic and functionality. 
- Resources :
This directory contains miscellaneous resources that do not fit into any of the other directories, such as fonts, sprites, or configuration files.
- Scenes :
This directory contains all of the project's scenes, which are the individual levels or screens that make up the game. 
- ProjectName :
This subdirectory contains the scenes for the project, organized by project name. 
- Scene :
This subdirectory contains the scene files for the project. 
- Project LightingData :
This subdirectory contains the LightingData and NavMesh files for the project, which are used to define the lighting and navigation data for the game.

Project Hierarchy

- Prerequisites :
This section contains all the game objects that is necessary for the current scene.
- Player :
This section contains all the game objects related to the player in the project.
- UI :
This section contains all the game objects related to the user interface in the project.
- World :
This section contains all the game objects related to the world in the project.
- Runtime :
This section contains all the game objects related to the runtime in the project.

<a align="center" name=" #structure-ProjectStructure"> Project Structure </a>

In this style, we will be using a structure that relies more on filtering and search abilities of the Project Window for those working with assets to find assets of a specific type instead of another common structure that groups asset types with folders.

> Using a prefix [naming convention](#asset-name-modifiers), using folders to contain assets of similar types such as `Meshes`, `Textures`, and `Materials` is a redundant practice as asset types are already both sorted by prefix as well as able to be filtered in the content browser.
<pre>
Assets
    <a name="#structure-developers">_Developers</a>(Use a `_`to keep this folder at the top)
        DeveloperName

    Art
		(Materials, Models, Shaders, Textures)
	Audio
		(AudioClip, AudioMixer, Music)
	Prefabs
	Scripts
	Documentation
		Oculus
		Plugins
		ProjectReferences
	Resources
	Scenes
		ProjectName
			Scene
		Project LightingData
			LightingData
		NavMesh
	StreamingAssets
		Hero.db3
	XR
	XRI


<h1 align="center" name="#structure-ProjectHierarchy">> Hero Cross Reality Application - Hierarchy Structure </h1>

<p align="center">This section describes the hierarchy of the game objects in the Unity project and their prerequisites.</p>

## Description


## Sections

> 1.0 [PREREQUISITES](#structure-PREREQUISITES) 

> 1.1 [PLAYER](#structure-PLAYER) 

> 1.2 [UI](#structure-UI) 

> 1.3 [WORLD](#structure-WORLD) 

> 1.4 [RUNTIME](#structure-RUNTIME) 

## Paths

<pre>
<a name="structure-PREREQUISITES">_PREREQUISITES</a>
	- LIGHTS
	- Audio
	- EFFECTS
	- EVENTS
	- ROUTINE & MANAGERS
<a name="structure-PLAYER">_PLAYER</a>
	- XR Rig Triage
	- Right Controller
	- Left Controller
	- TR_Bag
<a name="structure-UI">_UI</a>
	- SCREEN UI
	- WORLD UI
<a name="structure-WORLD">_WORLD</a>
	- INDOOR
	- BOUNDARIES
	- FLOOR
	- INTERACTABLES
	- TRIAGE	
<a name="structure-">_RUNTIME</a>
	- 
</pre>
