<h1 align="center"> Hero Cross Reality Application - Project Structure </h1>

This Unity project contains several Virtual Reality trainings and includes several directories with different types of assets, such as scripts, scenes, prefabs, textures, and audio files. In this README file, we will provide an overview of each directory and describe its contents.

## Sections

> 1.0 [Developers](#structure-Developers)

> 1.1 [Documentation](#structure-Documentation)

> 1.2 [Resources](#structure-Resources)

> 1.3 [Scenes](#structure-Scenes)

> 1.4 [StreamingAssets](#structure-StreamingAssets)

> 1.5 [XR](#structure-XR)


<a name="1.0"></a>
<a name="structure-Developers"></a>
### Developers

This directory includes files and documents intended for developers working on this project. It may contain guidelines, instructions, scripts, or other resources to facilitate the development process.

| Developer Name | Assets | Folders |
| -------------  | ------------- | ------------- |
| {DeveloperName} | Art | Materials, Models, Shaders, Textures |
|  | Audio | AudioClips, AudioMixers, Music |
|  | Prefabs | - |
|  | Scripts | - |

<a name="1.1"></a>
<a name="structure-Documentation"></a>
### Documentation

This directory contains the project's documentation, which may include user manuals, installation guides, or technical specifications.

<a name="1.2"></a>
<a name="structure-Oculus"></a>

- Oculus : If this project is intended for use with Oculus devices, this subdirectory may contain specific documentation related to Oculus integration.

<a name="1.3"></a>
<a name="structure-Plugins"></a>

- Plugins : This directory contains any plugins or external libraries used by the project.

<a name="1.4"></a>
<a name="structure-ProjectReferences"></a>

<p>
- Project References : 

<h2 align="center">Art</h2>

This subdirectory contains all of the project's art assets, such as :

- Materials
- Models
- Shaders
- Textures

<h2 align="center">Audio</h2>

This subdirectory contains all of the project's audio assets, such as :

- AudioClips
- AudioMixers
- Music

<h2 align="center">Prefabs</h2>
This subdirectory contains all of the project's prefabs, which are reusable game objects that can be used to quickly add functionality to a scene.

<h2 align="center">Scripts</h2>
This subdirectory contains all of the project's scripts, which are used to define the game's logic and functionality.

</p>

<a name="1.2"></a>
<a name="structure-Resources"></a>
### Resources

This directory contains miscellaneous resources that do not fit into any of the other directories, such as fonts, sprites, or configuration files.

<a name="1.3"></a>
<a name="structure-Scenes"></a>
### Scenes

This directory contains all of the project's scenes, which are the individual levels or screens that make up the game.

- ProjectName:
This subdirectory contains the scenes for the project, organized by project name.

- Scene:
This subdirectory contains the scene files for the project.

- Project LightingData:
This subdirectory contains the LightingData and NavMesh files for the project, which are used to define the lighting and navigation data for the game.

| Project Name | Scene | Project Lighting Data | Navmesh |
| -------------  | ------------- | ------------- | ------ |
|ACMC | Scene Files | Lighting Data | Navmesh Files|
|MCI | Scene Files | Lighting Data | Navmesh Files |
|COACE | Scene Files | Lighting Data | Navmesh Files |
|GTB | Scene Files | Lighting Data | Navmesh Files |
|UTSW | Scene Files | Lighting Data | Navmesh Files |

<a name="1.4"></a>
<a name="structure-StreamingAssets"></a>
### StreamingAssets

This directory contains any streaming assets used by the project, such as databases or other files used to store game data.

- Hero.db3
If the project includes a database, this file may contain the database used by the project.

<a name="1.5"></a>
<a name="structure-XR"></a>
### XR
This directory may contain any files related to XR (Extended Reality) integration, such as scripts or documentation.

<h1 align="center"> Hero Cross Reality Application - Hierarchy Structure </h1>

This section describes the hierarchy of the game objects in the Unity project and their prerequisites.

## Sections

> 2.0 [PREREQUISITES](#structure-PREREQUISITES)

> 2.0.1 [LIGHTS](#structure-LIGHTS)

> 2.0.2 [AUDIO](#structure-AUDIO)

> 2.0.3 [EFFECTS](#structure-EFFECTS)

> 2.0.4 [EVENTS](#structure-EVENTS)

> 2.0.5 [ROUTINE MANAGERS](#structure-ROUTINEMANAGERS)

> 2.1 [PLAYER](#structure-PLAYER)

> 2.2 [UI](#structure-UI)

> 2.3 [WORLD](#structure-WORLD)

> 2.4 [RUNTIME](#structure-RUNTIME)

<a name="2.0"></a>
<a name="structure-PREREQUISITES"></a>
### PREREQUISITES

<a name="2.0.1"></a>
<a name="structure-LIGHTS"></a>
- LIGHTS

<a name="2.0.2"></a>
<a name="structure-AUDIO"></a>
- AUDIO

<a name="2.0.3"></a>
<a name="structure-EFFECTS"></a>
- EFFECTS

<a name="2.0.4"></a>
<a name="structure-EVENTS"></a>
- EVENTS

<a name="2.0.5"></a>
<a name="structure-ROUTINEMANAGERS"></a>
- ROUTINE MANAGERS

<a name="2.1"></a>
<a name="structure-PLAYER"></a>
### PLAYER

- XR Rig TRIAGE
- Right Controller
- Left Controller
- TR_Bag

<a name="2.2"></a>
<a name="structure-UI"></a>
### UI

- SCREEN UI
- WORLD UI

<a name="2.3"></a>
<a name="structure-WORLD"></a>
### WORLD

- INDOOR
- BOUNDARIES
- FLOOR
- INTERACTABLES
- TRIAGE

<a name="2.4"></a>
<a name="structure-RUNTIME"></a>
### RUNTIME
