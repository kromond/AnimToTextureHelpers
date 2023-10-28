# AnimToTextureHelpers

Originally a fork of the excellent work from Kromond. But there were changes introduced in Unreal Engine 5.2 that break it up.

This repository is for Unreal Engine 5.3.1

# Go to plugin folder and copy:
the material, the texture, 

# Create the static mesh from the skeleton mesh using the BP utility BP_CreateSM

# Edit the data asset to put the Static Mesh

# Look the static mesh, and see the materials used

# Create material instances on those materials

# Edit the material instances
In details tab
![Alt text](image.png)

Select the ML_bonenamation material

Select the texture parameters values :

![Alt text](image-1.png)

copy the texture (UE5.3.1 crashes if there are no existing texture in the data asset, therefore we need to create the place holders)

# edit the 3rd blueprint so that it has the correct material instances

# Execute the 3rd blueprint

