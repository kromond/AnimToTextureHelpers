# AnimToTextureHelpers

Originally a fork of the excellent work from Kromond. But there were changes introduced in Unreal Engine 5.2 that break it up.
This repository is for Unreal Engine 5.3.1

## Approach
I used the assets contained in the Anim To Texture Folder.
I have created copy of them, which I include in this GIT Repository.

## Go to plugin folder and copy:
the material, the texture, 

## Create the static mesh from the skeleton mesh using the BP utility BP_CreateSM
Ensure that the data asset is correct in the blueprint
![Alt text](image-3.png)

## Edit the data asset to put the Static Mesh

## Look the static mesh, and see the materials used
Look at the material used in the Static Mesh. 
![Alt text](image-4.png)
You will need to instantiate them in the next step

## Create material instances on those materials
Right click the material and create a new instance
![Alt text](image-5.png)

## Edit the material instances
In details tab
![Alt text](image.png)

Select the ML_bonenamation material available in Plugings:
![Alt text](image-6.png)

Select the texture parameters values :

![Alt text](image-1.png)

copy the texture (UE5.3.1 crashes if there are no existing texture in the data asset, therefore we need to create the place holders)

## Edit the 3rd blueprint so that it has the correct material instances

## Execute the 3rd blueprint

