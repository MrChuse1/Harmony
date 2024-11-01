# Harmony
Harmony is a automation tool to generate USD files of assets from the Call of Duty engione.

It allows Call of Duty maps to be staged or imported into 3D applications; such as Maya, Blender, Houdini, and Unreal Engine

## Requirements
These tools are required for certain functionalities:

 - [Greyhound](https://github.com/Scobalula/Greyhound) by Scobabula for extracting models and textures
 - [Husky](https://github.com/Scobalula/Husky) by Scobabula for extracting the map file and geometry from a map

## Supported titles
- Black Ops III
- Black Ops 4

Others will added in the future. Requests will take priority

## Using Harmony
Using Harmony should be straight forward, fill in the required file paths and hit start.

 - Map Folder: This should be the folder of the map file extracted from Husky.
 - XModels Folder: This is the path to where your extracted models are. This path will also be used to find the ximages folder for textures extracted for the materials in the obj file.
 - Harmony Folder: Thisis where all your assets are stored. Models, materials and textures can be shared between maps.

## Notes
 - Material textures are automatically combined to save on storage space.
 - You can genereate a text file with a list of models or textures that need to be extracted in the Tools menu.
 - Models should be exported in the SEModel format.

-----
## Credits
The SEModel library was created by [Scobabula](https://github.com/Scobalula).
