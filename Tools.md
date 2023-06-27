# Tools

The editor functionality will be split amongst a slew of tools.

### Level editor

Scene editor for placing characters, prefabs, static meshes, effects, sounds, lights, etc. in the scene.

> Use Maya (or Blender; but preferably Maya as it is more popular) as the level editor.  
> Use the Maya C++ API (or the Maya Python API) for creating tools for -
- exporting Maya scenes, characters, animations, etc. to the Apex Game Engine format
- associating Maya scene elements to Apex game objects or entities
- attaching Apex-specific metadata to the various objects
- using Apex Game Engine materials and displaying 
- ... so on

### Visual Scripting editor

Defining character and game object behavior using visual data flow paradigm.

> Use WinForms for creating a standalone visual scripting tool

### Shader/Material editor

Defining procedural materials using data flow nodes and shader code scripting.

> Use WinForms for creating a standalone tool

### Build tool(s)

Command line (and GUI) tools for building various pipeline stages and projects using the correct environment.

> Use C++ and WinForms
