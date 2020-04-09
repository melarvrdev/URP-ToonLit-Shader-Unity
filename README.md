# Unity URP Simplified Toon Lit Shader Example (for you to learn writing custom lit shader in URP)

This repository is NOT the full version shader, the full version shader is still WIP and not yet released.
This repository is only for tutorial purpose, which only contains a very simple and short shader example.

Screenshots from the Full version shader (not yet released):
-------------------
BEFORE
![screenshot](https://i.imgur.com/AMDcMdG.png)
AFTER
![screenshot](https://i.imgur.com/GB31Nay.png)
video -> https://youtu.be/ZfSZOHTBypc

BEFORE
![screenshot](https://i.imgur.com/UCETVsr.png)
AFTER
![screenshot](https://i.imgur.com/7Wjdp8W.png)
video -> https://youtu.be/EgxiWPk-vaE

BEFORE
![screenshot](https://i.imgur.com/5afc5z5.png)
AFTER
![screenshot](https://i.imgur.com/pQ4DIqe.png)
video -> https://youtu.be/Ty4DXLFqqDo

BEFORE
![screenshot](https://i.imgur.com/WKL3NwV.png)
AFTER
![screenshot](https://i.imgur.com/8e6wtVZ.png)
video -> https://youtu.be/cebGl_MaWnI

Fake Skin SSS & specular
![screenshot](https://i.imgur.com/ZoDO5TB.png)
![screenshot](https://i.imgur.com/ICH4dFt.png)

BEFORE
![screenshot](https://i.imgur.com/dPvjIQK.png)
AFTER
![screenshot](https://i.imgur.com/GvxXtva.png)



What is included in this "simplified version" toon lit shader repository?
-------------------
This repository contains a very simple toon lit shader example, to help people writing their first custom toon lit shader in URP.

This example shader's default result(without editing material params) = the following picture
![screenshot](https://i.imgur.com/mbUnvsA.png)

Because this example toon lit shader aims to help people learning shader writing in URP, it is an extremely simplified version of the full version one. This repository only contains ~10% of the full version shader, which only contains the most useful & easy to understand sections, to make sure everyone can understand the shader code easily.

It is actually a "How to write your first custom lit shader in URP" example, instead of a good looking toon lit shader example (lots of toon lit tricks are not included in this example shader, for tutorial reason).

Why creating this "simplified version" toon lit shader?
-------------------
Lots of my shader friends are looking for a toon lit example shader in URP (not Shader Graph), I want them to switch to URP with me (instead of still staying in built-in RP), so I decided to provide a simple enough URP toon lit shader example. 

How to try this simplified toon lit example shader in my URP project?
-------------------
1. Clone all .shader & .hlsl files into your URP project.
2. Put these files inside the same folder.
3. Change your character's material's shader to "SimpleURPToonLitExample(With Outline)"
4. make sure atleast _BaseMap(albedo) is assigned
5. setup DONE, you can now test your character with light probe/directional light/point light/spot light
6. edit the material properties to see how the render result changes
7. Most important: open these shader files, spend some time reading it, you will understand how to write custom lit shader in URP very quickly
8. Most important: open "SimpleURPToonLitOutlineExample_LightingEquation.hlsl", edit it, experiment with your own toon lighting equation ideas, which is the key part of toon lit shader!

What is NOT included in this simplified example shader?
-------------------
For simplicity reason, I removed most of the features from the Full version shader (deleted 90% of the original shader), else this example shader will be way too complex for reading & learning. The removed features are:
- face sphere proxy normal & direction proxy normal (fixing face ugly normals, very important)
- smooth outline normal auto baking (fixing ugly outlines, very important)
- constant outline fix for fov and distance to camera (outline looks correct in any situation, very important)
- tricks to remove unwanted hair shadow casted on face (to keep face looks clean, very important)
- tricks to render eye over hair
- hair "angel ring" reflection
- sharp rim light
- PBR specular lighting (GGX)
- HSV control shadow & outline color
- 2D mouth renderer
- stencil local hair shadow on face
- physics and wind

- almost all the extra texture input options like AO, specular, normal map...
- LOTS of sliders to control lighting, final color & outline
- ***just too much for me to write all removed feature here, the full version shader is a totally different level product

When will the Full version toon lit shader release?
-------------------
We don't have ETA now, we are still working on it, here are some videos about the Full version toon lit shader:
- https://youtu.be/uVI_QOioER4
- https://youtu.be/YtAiCHBvZr0
- https://youtu.be/QWB060rVjFI
- https://youtu.be/URVgKT5c3PM
- https://youtu.be/6Gx0LxByfWk
- https://youtu.be/IP293mAmBCk
- https://youtu.be/n_bFQ9GNhcM
- https://youtu.be/HmuaWpL5Pi8
- https://youtu.be/tNnqIP4NdV8 (current)
- https://youtu.be/ZfSZOHTBypc (current)
- https://youtu.be/cebGl_MaWnI (current)
- https://youtu.be/Ty4DXLFqqDo (current)
- https://youtu.be/EgxiWPk-vaE (current)

How to get a test character model?
-------------------
The easiest way to get a character model is by downloading Unity-Chan in the assetstore.

Also, here are some websites that can download models(If the creator allows it)
- https://3d.nicovideo.jp/
- https://hub.vroid.com/

if you downloaded a .pmx file, use this to convert it to .fbx & prefab directly inside unity

MMD4Mecanim (Beta)
http://stereoarts.jp/

if you downloaded a .vrm file, use this to convert it to .fbx & prefab directly inside unity

UniVRM
https://github.com/vrm-c/UniVRM

Editor environment requirement
-----------------------
- URP 7.2.1 or above
- Unity 2019.3 or above

---------------------------
More old screenshots from the Full version shader(not yet released):
---
![screenshot](https://i.imgur.com/RDqMYVP.png)
![screenshot](https://i.imgur.com/AqqXbjz.png)
![screenshot](https://i.imgur.com/m95orpw.png)
![screenshot](https://i.imgur.com/1uU9Dp1.png)
![screenshot](https://i.imgur.com/U2XYPAj.png)
![screenshot](https://i.imgur.com/23eeHZS.png)
![screenshot](https://i.imgur.com/pMCxwyP.png)
![screenshot](https://i.imgur.com/sxeUg1K.png)
https://youtu.be/tNnqIP4NdV8
---
Apply our shader to another model (2020-2 early version screen shots)
![screenshot](https://i.imgur.com/KxdjhCx.png)
![screenshot](https://i.imgur.com/6t2FMcg.png)
![screenshot](https://i.imgur.com/LBTNZCH.png)
![screenshot](https://i.imgur.com/X6hAD7W.png)
![screenshot](https://i.imgur.com/WIGyMVx.png)
![screenshot](https://i.imgur.com/zou7PxL.png)
![screenshot](https://i.imgur.com/CZHnfMC.png)
(2020-3 early version screen shots)
![screenshot](https://i.imgur.com/WpkJyFB.png)
![screenshot](https://i.imgur.com/3iyu3eG.png)



![screenshot](https://i.imgur.com/DDr32Mu.png)
https://youtu.be/IP293mAmBCk

![screenshot](https://i.imgur.com/kbpw4Me.png)
![screenshot](https://i.imgur.com/jaMaTKt.png)
![screenshot](https://i.imgur.com/D7ARBo0.png)

![screenshot](https://i.imgur.com/lt45arW.png)
![screenshot](https://i.imgur.com/RcSz8H1.png)


