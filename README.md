<h1 align="center"> Hero Cross Reality Application - Project Structure </h1>

This Unity project contains several Virtual Reality trainings and includes several directories with different types of assets, such as scripts, scenes, prefabs, textures, and audio files. In this README file, we will provide an overview of each directory and describe its contents.



## Description

| Developers | Art | Audio |
| :---: | :---: | :---: |
| This directory includes files and documents intended for developers working on this project. It may contain guidelines, instructions, scripts, or other resourcesto facilitate the development process. | This subdirectory contains all of the project's art assets, such as materials, models, shaders, and textures. | This subdirectory contains all of the project's audio assets, such as AudioClips, AudioMixers, and music. |

| Prefabs | Scripts | Documentation |
| :---: | :---: | :---: |
| This subdirectory contains all of the project's prefabs, which are reusable game objects that can be used to quickly add functionality to a scene. | This subdirectory contains all of the project's scripts, which are used to define the game's logic and functionality. | This directory contains the project's documentation, which may include user manuals, installation guides, or technical specifications. |

| Resources | Scenes | StreamingAssets |
| :---: | :---: | :---: |
| This directory contains miscellaneous resources that do not fit into any of the other directories, such as fonts, sprites, or configuration files. | This directory contains all of the project's scenes, which are the individual levels or screens that make up the game. | This directory contains any streaming assets used by the project, such as databases or other files used to store game data. |

| XR/XRI |
| :---: |
| This directory may contain any files related to XR (Extended Reality) integration, such as scripts or documentation. |

## Table of Contents

> 1.0 [Developers](#structure-Developers) 

> 1.1 [Art](#structure-Art) 

> 1.2 [Audio](#structure-Audio) 

> 1.3 [Prefabs](#structure-Prefabs) 

> 1.4 [Scripts](#structure-Scripts) 

> 1.5 [Documentation](#structure-Documentation) 

> 1.6 [Resources](#structure-Resources) 

> 1.7 [Scenes](#structure-Scenes) 

> 1.8 [StreamingAssets](#structure-StreamingAssets) 

> 1.9 [XR](#structure-XR) 

> 2.0 [XRI](#structure-XRI)

<pre>

<a name="structure-Developers">
	_Developers</a>

		- [DeveloperName]
<a name="structure-Art">
	_Art</a>

		- Materials
		
		- Models
		
		- Shaders
		
		- Textures
	<a name="structure-Audio">	
	_Audio</a>
	
		- AudioClip
		
		- AudioMixer
		
		- Music
	<a name="structure-">	
	_Prefabs</a>
		
		- 
		
<a name="structure-">
	_Scripts</a>
	
		-

	_<a name="structure-Documentation">Documentation</a>

		- <a name="structure-Oculus">Oculus</a>

		- <a name="structure-Plugins">Plugins</a>

		- <a name="structure-ProjectReferences">ProjectReferences</a>

		<a name="structure-">
	_Resources</a>
		
		-
			
		<a name="structure-Scenes">	
	_Scenes</a>

		- ProjectName
				
			- Scene
				
		- Project LightingData
			
			- LightingData
			
		- NavMesh

		<a name="structure-StreamingAssets">
	_StreamingAssets</a>

		- Hero.db3

		<a name="structure-">
	_XR</a>
			
		-

		<a name="structure-">
	_XRI</a>
		
		-

</pre>

<a name="1.0"></a>
<a name="structure-Developers"></a>

<h1 align="center"> Hero Cross Reality Application - Hierarchy Structure </h1>

This section describes the hierarchy of the game objects in the Unity project and their prerequisites.

## Sections

> 1.0 [PREREQUISITES](#structure-PREREQUISITES) (This section contains all the game objects that is necessary for the current scene.)

> 1.1 [PLAYER](#structure-PLAYER) (This section contains all the game objects related to the player in the project.)

> 1.2 [UI](#structure-UI) (This section contains all the game objects related to the user interface in the project.)

> 1.3 [WORLD](#structure-WORLD) (This section contains all the game objects related to the world in the project.)

> 1.4 [RUNTIME](#structure-RUNTIME) (This section contains all the game objects related to the runtime in the project.)

<pre>

<a name="structure-PREREQUISITES">
	_PREREQUISITES</a>

		- LIGHTS
	
		- Audio
	
		- EFFECTS
	
		- EVENTS
	
		- ROUTINE & MANAGERS
		
<a name="structure-PLAYER">
	_PLAYER</a>
		
		- XR Rig Triage
	
		- Right Controller
		
		- Left Controller
		
		- TR_Bag

<a name="structure-UI">
	_UI</a>
		
		- SCREEN UI
	
		- WORLD UI

<a name="structure-WORLD">
	_WORLD</a>

		- INDOOR

		- BOUNDARIES
	
		- FLOOR
	
		- INTERACTABLES
	
		- TRIAGE
			
<a name="structure-">
	_RUNTIME</a>
		
		- 
</pre>
