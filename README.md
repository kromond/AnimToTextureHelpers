# AnimToTextureHelpers

Update 19 Aug 2024: A PR was merged from a [tomaaron](https://github.com/tomaaron) updating to 5.3

A PR was merged from user @Bobble68 updating this to now work with Unreal Engine 5.2.  Thanks @Bobble68, you are the hero of many.  The 5.1 version was moved to a branch.  

This plugin will create vertex animation textures in Unreal Engine, taking a Skeletal Mesh and a set of animations and creating a static mesh and textures which will animate that static mesh.  This could be used to make a crowd, for example.


One UASSET is an Editor Utility Blueprint used to make vertex animation textures and related assets for bone based VAT motion.  The other UASSET is a blueprint for instancing a static mesh with vertex animation textures.  Copy these to your project content folder.  They work in Unreal Engine 5.2

These are offered as a demonstration or example only, no support or guarantee is offered.  It’s likely these would need modification for your use case.

NOTE: Clone the repo or download the files individually.  A user has noted that when using the "download zip" feature, the binary files get corrupted and won't be recognized in UE.

A video on these can be found here:
https://youtu.be/vrlFozqB0jA

![HighresScreenshot00015](https://user-images.githubusercontent.com/5624947/211672718-688c375f-e9b9-4872-85d8-2ba624694084.png)
