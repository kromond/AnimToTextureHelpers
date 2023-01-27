# AnimToTextureHelpers

Fork of the excellent work from Kromond

These are  UASSETS for Unreal Engine 5.1 to help with using the AnimToTexture plugin.  This plugin will create vertex animation textures in Unreal Engine, taking a Skeletal Mesh and a set of animations and creating a static mesh and textures which will animate that static mesh.  This could be used to make a crowd, for example.



One UASSET is an Editor Utility Blueprint used to make vertex animation textures and related assets for bone based VAT motion.  

The other UASSET are blueprints for instancing a static meshes with vertex animation textures.

The original one from Kromond (updated to remove a useless for loop)
One currently working with 2 Static meshes
The other one with array of static mesh, but which doesn't work correctly yet : all instances are looping on all animation.



Copy these to your project content folder.  They work in Unreal Engine 5.1

These are offered as a demonstration or example only, no support or guarantee is offered.  It’s likely these would need modification for your use case.

NOTE: Clone the repo or download the files individually.  A user has noted that when using the "download zip" feature, the binary files get corrupted and won't be recognized in UE.

A video on these can be found here:
https://youtu.be/vrlFozqB0jA

![HighresScreenshot00015](https://user-images.githubusercontent.com/5624947/211672718-688c375f-e9b9-4872-85d8-2ba624694084.png)
