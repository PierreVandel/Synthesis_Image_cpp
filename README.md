# image_synthesis_cpp

Based on the code of Marie-Ange LEBRE.

3D scene rendering algorithms making it possible to switch from a three-dimensional scene to a projection of this scene on a two-dimensional screen in order to be able to visualize it (Z-buffer, illumination,  quadrics implementation,  gouraud shading, phong shading, texturing)

## Setup
If you have problems while running the program, try cleaning up the solution, then in the project properties -> linkers -> Activation of incremental links put on "no". Then click on Apply at the bottom right. Finally generate the solution

After running the program, to create a scene: File > New Scene. To insert a quadric: Insert > Revolution cylinder (for example). When inserting a quadric, in these properties, you can add a texture to it. To add a light: Insert > Light source. To control the camera: Display > Camera controls.

Phong shading, is already enabled by default.

For texturing, an image is provided for you to try. To test the texturing, you need to add the image in the properties when implementing any quadric in the texture section

For other features, I'll let you discover.
