# Unity Shader Workshop
###### June 2019 @ Parsons School of Design, Design and Technology, Summer Dorkshop
###### [Jungu Guo](http://www.junguguo.com/) 
guoj038@newschool.edu

## DESCRIPTION
This introductory yet intensive workshop explores the fundamentals of GPU-based graphics programming in Unity, with particular emphasis on understanding the rendering pipeline, learning the math and algorithms relevant to graphics and writing vertex shader, fragment shader, surface shader, compute shader and post-proessing shader with the ShaderLab language provided by Unity. 

## LEARNING OUTCOME
1. A bird’s-eye view of what rendering is, what a shader is and how it fits into the rendering process. 
2. The technical skills necessary to create different types of shaders in Unity (surface, vertex, fragment, compute shader, post-processing)
3. A thorough understanding of the common techniques of mathematics and algorithms needed to create generative visuals
4. ..



## RESOURCES
**Documentation**
- http://docs.unity3d.com/Manual/SL-Reference.html
- NVIDA


**Books** (in order of beginner to advanced)
- [Unity 2018 Shaders and Effects Cookbook 3rd Edition](https://www.amazon.com/Unity-2018-Shaders-Effects-Cookbook/dp/1788396235/ref=sr_1_1?keywords=unity+shader&qid=1560329187&s=gateway&sr=8-1)
- [Practical Shader Development](https://www.amazon.com/Practical-Shader-Development-Fragment-Developers/dp/1484244567/ref=sr_1_6?keywords=unity+shader&qid=1560329194&s=gateway&sr=8-6)
- [Unity Shader 入门精要 (in Chinese)](https://github.com/candycat1992/Unity_Shaders_Book)
- [The Book of Shaders](https://thebookofshaders.com/) 
- [Unity Graphics Programming (in Japanese)](https://indievisuallab.stores.jp/) 

**Tutorials, Website and People**
- [Writing Shaders - Unity Official Tutorials](https://docs.unity3d.com/Manual/ShadersOverview.html)
- [CatLikeCoding](http://catlikecoding.com/)
- [Inigo Quilez](http://www.iquilezles.org/www/index.htm)
- [Keijiro Takahashi](https://github.com/keijiro)
- [Alastair Aitchison](https://alastaira.wordpress.com/tag/shader/)

**Other**
- [ShaderToy](https://www.shadertoy.com/)

<br>

***

<br>

## SYLLABUS 
> Note: Use this syllabus as a checklist to recall the key points covered in lectures. When you feel fuzzy about the concepts then check out the slides for more details.
### **Session 1: Introduction to Shader** (10:30 am - 5:00pm, Tue, June 11 )
##### 1. 	What is Shader?
##### 2. 	CPU computing vs GPU computing
##### 3. 	**Rendering Pipeline**
- Application -- **Vertex Shader** -- Tessellation -- **Geometry Shader** -- (Rasterization) -- **Fragment Shader** -- (Framebuffer)

##### 4. 	**Mathematics**
- Matrix and Coordinate System
- Trigonometry
- Vector
  - Tangent, Normal, Bi-tangent
  - Dot, Cross
  - View Direction, Light Vector
- CG Functions and API detail

##### 5. 	**Textures**
- uv and texture mapping
- Different Types of texture
  - albeto, normal map, height map
- Channels of texture

##### 6. 	**Lighting Model and Effect**
##### 7. 	**Languages of Shader**
- GLSL (OpenGL) :
  - OpenGL for shading language
- HLSL (DirectX) :
  - High Level shading language
- Cg (NVidia) : 
  - C for graphics
- (With Unity you can use any of these three)

#####  	**##  Assginment ##**
###### Reading
1. *Chapter 10: Normal Mapping* — [Practical Shader Development](https://www.amazon.com/Practical-Shader-Development-Fragment-Developers/dp/1484244567/ref=sr_1_6?keywords=unity+shader&qid=1560329194&s=gateway&sr=8-6)
2. Check out Patricio Gonzalez's video lecture on Shaders: [Shaders, a computational language of light - GROW 2018](https://www.youtube.com/watch?v=Au3zQwJj5AU)

###### Coding
1. Try to recreate all the in-class examples from scratch
2. Go over the per-vertex lighting example and try to implement a per-pixel diffuse lighting model 
3. Go over the Unity surface shader examples and create your own surface shader

<br>

### **Session 2: TBA**
##### 1. 	Noise
##### 2.  Lighting Models
##### ..


<br>


***

<br>

## CODE & EXAMPLE 
### 01 HelloShader



