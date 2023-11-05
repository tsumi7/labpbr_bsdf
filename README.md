# LabPBR -> BSDF
Blender OSL Shader for connecting LabPBR inputs to Principled BSDF. It's not perfect, but provides a decent starting point for viewing LabPBR textures within Blender or other renderers supporting the Open Shading Language.

## Example Node Setup
> [!NOTE]
> Using 'closest' instead of 'linear' sampling may improve the performance of lower resolution textures, though this is more of a stylistic choice.

![image](https://github.com/tsumi666/labpbr_bsdf/assets/90137856/3b177335-80e6-4669-965e-07d1cebfd07c)

> [!WARNING]
> Make sure your texture inputs for normal and specular are set to 'Non-Color' or 'Raw'.

## Example Render

Gold Ore rendered using AVPBR and 128x subdivision on a cube mesh.

https://github.com/tsumi666/labpbr_bsdf/assets/90137856/16891ba0-f177-416c-81e8-b455bd425940

