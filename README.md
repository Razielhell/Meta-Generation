# Hero Cross Reality Application - Project Structure and Hierarchy Documentation
This document provides an overview of the Unity Editor structure for the Hero Cross Reality Application project. It outlines the Hierarhy and Project Structure including the different directories and subdirectories that contain the project.
# Table of Contents
- [1.0 Project Structure](#project-structure)
- [1.1 Project Structure Description](#project-structure-description)
- [2.0 Project Hierarchy](#project-hierarchy)
- [2.1 Project Hierarchy Description](#project-hierarchy-description)
- [Asset Name Modifiers](#asset-name-modifiers)
## Project Structure
This is the Project Structure that we use.
- `Assets`
  - `_Developers`
    - `{_DeveloperName}`
      - `Art`
        - `Materials`
        - `Models`
        - `Shaders`
        - `Textures`
      - `Audio`
        - `AudioClip`
        - `AudioMixer`
        - `Music`
      - `Prefabs`
      - `Scripts`
      - `Documentation`
        - `Oculus`
        - `Plugins`
        - `ProjectReferences`
        - `Resources`
        - `Scenes`
      - `ProjectName`
        - `Scene`
      - `Project LightingData`
        - `LightingData`
      - `NavMesh`
      - `StreamingAssets`
        - `Hero.db3`
      - `XR`
      - `XRI`
## Project Structure Description
| Directory | Description |
| --- | --- |
| Developers | This directory includes files and documents intended for developers working on this project. It may contain guidelines, instructions, scripts, or other resources to facilitate the development process. |
| DeveloperName | This subdirectory includes resources specific to individual developers working on the project. |
| Art | This subdirectory contains all of the project's art assets. |
| | Materials |
| | Models |
| | Shaders |
| | Textures |
| Audio | This subdirectory contains all of the project's audio assets. |
| | AudioClip |
| | AudioMixer |
| | Music |
| Prefabs | This subdirectory contains all of the project's prefabs, which are reusable game objects that can be used to quickly add functionality to a scene. |
| Scripts | This subdirectory contains all of the project's scripts, which are used to define the game's logic and functionality. |
| Documentation | This directory contains the project's documentation, which may include user manuals, installation guides, or technical specifications. |
| | Oculus | If this project is intended for use with Oculus devices, this subdirectory may contain specific documentation related to Oculus integration. |
| | Plugins | This directory contains any plugins or external libraries used by the project. |
| | ProjectReferences | This directory contains subdirectories with different types of assets used in the project. |
| | Resources | This directory contains miscellaneous resources that do not fit into any of the other directories, such as fonts, sprites, or configuration files. |
| | Scenes | This directory contains all of the project's scenes, which are the individual levels or screens that make up the game. |
| ProjectName | This subdirectory contains the scenes for the project, organized by project name. |
| | Scene | This subdirectory contains the scene files for the project. |
| ProjectLightingData | This subdirectory contains the LightingData and NavMesh files for the project, which are used to define the lighting and navigation data for the game. |
| NavMesh | This subdirectory contains the NavMesh files for the project. |
| StreamingAssets | This subdirectory contains additional assets used in the project, such as the "Hero.db3" database file. |
| XR | This subdirectory contains assets specific to cross-reality applications. |
| XRI | This subdirectory contains assets specific to cross-reality interactions. |
## Project Hierarchy
This is the Project Hierarchy that we use.
- `PREREQUISITES`
    - `LIGHTS`
    - `Audio`
    - `EFFECTS`
    - `EVENTS`
    - `ROUTINE & MANAGERS`
  - `PLAYER`
    - `XR Rig Triage`
    - `Right Controller`
    - `Left Controller`
    - `TR_Bag`
  - `UI`
    - `SCREEN UI`
    - `WORLD UI`
  - `WORLD`
    - `INDOOR`
    - `BOUNDARIES`
    - `FLOOR`
    - `INTERACTABLES`
    - `TRIAGE`
  - `RUNTIME`
## Project Hierarchy Description
| Directory | Description |
| --- | --- |
| Prerequisites | This section contains all the game objects that are necessary for the current scene. |
| | LIGHTS: This subdirectory contains all the light game objects used in the project. |
| | Audio: This subdirectory contains all the audio game objects used in the project. |
| | EFFECTS: This subdirectory contains all the effects game objects used in the project. |
| | EVENTS: This subdirectory contains all the events game objects used in the project. |
| | ROUTINE & MANAGERS: This subdirectory contains all the game objects related to routine and managers. |
| Player | This section contains all the game objects related to the player in the project. |
| | XR Rig Triage: This subdirectory contains all the game objects related to the XR rig triage. |
| | Right Controller: This subdirectory contains all the game objects related to the right controller. |
| | Left Controller: This subdirectory contains all the gameobjects related to the left controller. |
| | TR_Bag: This subdirectory contains all the game objects related to the TR bag. |
| UI | This section contains all the game objects related to the user interface in the project. |
| | SCREEN UI: This subdirectory contains all the screen user interface game objects. |
| | WORLD UI: This subdirectory contains all the world user interface game objects. |
| WORLD | This section contains all the game objects related to the world in the project. |
| | INDOOR: This subdirectory contains all the indoor game objects. |
| | BOUNDARIES: This subdirectory contains all the boundary game objects. |
| | FLOOR: This subdirectory contains all the floor game objects. |
| | INTERACTABLES: This subdirectory contains all the interactable game objects. |
| | TRIAGE: This subdirectory contains all the triage game objects. |
| RUNTIME | This section contains all the game objects related to the runtime in the project. |
## Asset Name Modifiers
By using this naming convention, it is unnecessary to group asset types with folders, as asset types are already sorted by prefix and can be easily filtered in the content browser. For more information on the naming convention used in this project, please refer to the [NameConvention.md](https://github.com/atsdevelopers/HeroCrossRealityApplication/blob/develop/NameConvention.md) document.
## Conclusion
This Git documentation provides an overview of the Project and Hierarchy structure for the Hero Cross Reality Application. By following these guidelines and best practices, we can ensure a smooth and organized development process for the project.
 Happy Coding!







