# Entry 5
##### 4/11/2025

# Context:
For my freedom project, I have tinkered with Aframe which is a tool that supports HTML codes to create a 3D virtual reality experience for users diving into a unique scene that can contain entities, adjusting the brightness by adding light entity, creating a plane, using environmental component to set up a scene, etc... All of which Aframe offers for the starter building a scene tutorial. Most of the components offered by Aframe I have tried is... When tinkering with Aframe, I went onto [A-Frame's official website](https://aframe.io/) that provides various codes that you can use to experiment with Aframe and what the tool offers. On the otherhand, I tested these Aframe concept with [Jsbin](https://jsbin.com) which helps me test out my code when I am trying to learn what the Aframe code does. 

Below is the code I made a basic scene of using the following concepts:
* Textured Plane
* Sky Background
* 3D figures (Entities)
* Expanding tiles on the textured plane
* Adding light entities (I used ambient but you can also use directional if you want to cast shadows)
* Animation property

```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>Tinkering with concepts taught in the creating a basic scene in Aframe:</title>
    <script src="https://aframe.io/releases/1.7.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-sky src="https://cdn.aframe.io/360-image-gallery-boilerplate/img/sechelt.jpg"></a-sky>
      <a-plane src="https://cdn.aframe.io/a-painter/images/floor.jpg" position="0 0 0" rotation="-90 0 0" width="10" height="10" material="repeat: 10 10"></a-plane>
      <a-sphere position="0 2 3" radius="1" color="lime"></a-sphere>
      <a-cylinder position="0 2 -3" radius="1" color="white"></a-cylinder>
      <a-box position="0 2 -3" width="2" height="2" color="yellow" animation="property: rotation; to: 0 360 0; loop: true; dur: 1000"></a-box>
      <a-light type="ambient" intensity="3" color="#ffffff"></a-light>
      <a-camera position="-9 3 0"></a-camera>
    </a-scene>
  </body>
</html>
```
Below is a code I used for...
* Using the environmental component (**make sure to have the environmental component link first in between the head before importing an environmental component setting**)
* Applying textures to entities

```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>Try out an Environmental Component!</title>
    <script src="https://aframe.io/releases/1.7.0/aframe.min.js"></script>
    <script src="https://unpkg.com/aframe-environment-component@1.3.x/dist/aframe-environment-component.min.js"></script>
  </head>
  <body>
    <a-scene>
        <a-box src="https://i.imgur.com/mYmmbrp.jpg" position="0 2 -5" rotation="0 45 45" scale="2 2 2"></a-box>
        <!-- Out of the box environment! -->
        <a-entity environment="preset: japan; dressingAmount: 500"></a-entity>
    </a-scene>
  </body>
</html>
```

# Skills:
* **Problem-solving**: A lot of problem solving comes with tinkering codes, comprehending and making sure to understand the concept. When tinkering with Aframe, the most necessary thing to learn our tool is by tinkering with curiousity, first curiousity leads us to exploring the concept deeper. Normally, when we are tinkering, we face problems like coding errors, and we often don't go beyond since we are given the option to give up in the face of obstacles. The skill, Problem solving, is essential because it's a personal skill that requires perservance to keep on going and to solve errors instead of just giving up.
* **Time managment**: Managing my time effectively when we were given time in class to tinker with Aframe. With our final learning of our tool by wrapping up the final learning contents. Even though, I didn't get to explore the entire Aframe components and other features Aframe offers. However, it's essential to learn some of Aframe which allows us to use Aframe to build a scene that could really stand out when applying to my final freedom project. 

# Next steps:
After tinkering with Aframe, I would plan to use my freetime to explore Aframe and uncover more concepts to put into use for my final freedom project. Additionally, I want to plan how my website should look with Aframe, making a wireframe for the designs such as adding sections where I can add my scene in.

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
