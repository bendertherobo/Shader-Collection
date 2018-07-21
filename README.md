# Shader-Collection
Collection of shaders i've made with documentation to explain some of the effects with videos.
Notes-
1) A grabpass shader is a shader that renders a texture or effect over a players camera while in the object the shader is on, these shaders DO NOT go on your model, but on an shape, usually a sphere around your model.
2) Any shader marked with a ** needs a directional light attatched to the object the shader is on, the directional light needs to have intensity at .001 and hard shadows set. all other options should be default.

AfterImage shader - Grabpass
A simple shader that quadruples everything you see, contains a slider to increse the strength.

Video:https://streamable.com/08pc5

ArrowTravel Shader (icludes transparent version)
A shader that causes mesh particles to allign to velocity when rendered in world space simulation.

Video:https://streamable.com/cys5p

Blur and pixel shader - Grabpass
A shader that blurs or pixelates everything in the area, can adjust the strength of both effects,

Video:https://streamable.com/yjbn6

Cloth Particle Dissolve
A shader that emulates dissolving into particles, can adjust dissolve strength, noise texture of the dissolve,and the edge color for the dissolve, best when used with black and white flow textures.

Video:https://streamable.com/9z6h8

Configurable UI - Grabpass
a UI set up shader with 9 texture slots that can all be completely adjusted placement wise, textures for this should be 1920 x 1080 black backgrounds with white ui elements in the rough places you want them on screen, any texture slots you dont need keep filled with a full black texture. Certain texture slots support fading and increasing or decreasing opacity.

Video:https://streamable.com/8v88b

Disentigrate shader
A shader that disentigrates a mesh over a noise texture with noise warping, slider adjusts the dissolve amount.

Video:https://streamable.com/e8g17

Grabpass- Grabpass
A grabpass shader that can apply noise textures over the screen, can also desaturate and greyscale.

Video:https://streamable.com/pdc6k / https://streamable.com/xunuh

Screenfade - Grabpass
A simple shader that fades out the screen. Shader Edited

Video:https://streamable.com/c1oss 

Texture Swap
A shader that can dissolve between two scrollable textures based on a noise profile, also supports outlines, good for transformation effects.

Video: https://streamable.com/sbrru

Wireframe - **
A shader that displays the polys of models. Shader edited.

Video: https://streamable.com/2kfjr

World based dissolve (zelda dissolve)
A version of the disentigrate shader that uses world based motion instead of mesh warping

Video:https://streamable.com/f0vx2

Flat-lit mesh warp (bender's all-in-one shader)
A shader that supports:
Main texture that is
 
 -Scrollable
 
 -rotatable
 
 -pixalate
 
 -Cellshadable
 
 -Scrolling noise texture UV warpable
 
 -Scaleable

Normal Emission mapping

Custom Waveform Emission with
 
 -Waveform amount control
 
 -Waveform type control (vert/horizon)
 
 -Emission strength
 
 -Two colors
 
 -Moving emission
 
 -Warping the mesh based on these waveforms

Mesh warping based on a scrollable Noise texture

Heightmapping supporting

-Scrolling

-Pulsing based on a min and max

-Rotation

Animated Tessalation

Fur tessalation (just intensifies the tessalation)

Outline supporting

-Scrolling

-Color

-Texture outlines

-Noise warping of the outline

Overlays supporting

-Transparency

-scrolling

-scrollable UV noise warping

-pixellation

-World space overlay

-Screenspace overlay

Edge glow with adjustable size, hardness, and color.

Videos:https://streamable.com/zzwqp

https://streamable.com/ygf7i

https://streamable.com/rj8zt

https://streamable.com/as48m

https://streamable.com/98qvg

https://streamable.com/4rr94

https://streamable.com/zv0il

https://streamable.com/uplic


NEW AS OF V2

Custom Animated Outline
A standard flatlit shader with a highly customizable outline.
Video: https://streamable.com/fqegn

CubeMap Skybox
Just a shader that fixes the inverted skybox when using a cubemap
Video: https://streamable.com/k6czm

Black Hole
A customizable black hole shader that fits most mesh types.
Video: https://streamable.com/d0478

Fur Shader
Uses Tesselation and rotation to create a fur look
Video: https://streamable.com/zuc1e

BlackandWhite+inversion
Grabpass a few screenspace effects in one shader
Video: https://streamable.com/cbklk

Holo Shield
Video: https://streamable.com/hlz59

Glitch Shader
Video: https://streamable.com/rylv4
