# Tool Learning Log

## Tool: A-Frame

---

### 3/9/2025:
I tinkered with the starter code of A-Frame and investigated on some of the properties within the HTML code. I also used videos from youtube and the A-frame website to get to know what A-Frame uses and offers to users who plan to use A-frame to code and make use of the tool. 

* [A-Frame](https://aframe.io/docs/1.7.0/introduction/)
* ["What is Aframe?"](https://www.youtube.com/watch?v=ktjMCanKNLk)

<br>

First, I tinkered with the starter code by changing the position of each component, **changing the color of the 3D figures, and changing the color of the sky background**.
  * ``position="x y z"`` **(x moves horizontally, y moves vertically, and z moves front of back)**
  * ``color="#0000FF"`` **(change the color of the object by assigning a hex code. For example, in this code the hexcode #0000FF is the color assigned to blue)**

<br>

Besides just changing the position and color, the next steps I wanted to do was to tinker with the code by **changing the rotation and radius**.
  * ``rotation="a b c"`` **(a is the rotation around the x-axis, b is the rotation around the y-axis, c is the rotation around the z-axis)**
  * ``radius="#"`` **(adjusting the thickness of the 3D figures. For example, the larger the #, the bigger the shape is. Whereas, the lower the #, the smaller the shape is.)**

<br>

Below is the starter code I tinkered before I tried changing the rotation and radius:

```HTML
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position="-3 2 1" rotation="0 45 0" color="#A020F0"></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#0000FF"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#00FF00"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#00008B"></a-sky>
    </a-scene>
  </body>
</html>
```
<hr>

### 3/15/2025:
After scrolling on the Aframe, I found the Aframe guide section, I checked out the Building Basics Scene and found out how I could change the background to something else rather than sky. Learning this could allow me to change the background to something else that actually matches with the following theme I plan to create using Aframe.

* [Aframe Guide: Building a Basic Scene](https://aframe.io/docs/1.7.0/guides/building-a-basic-scene.html)

```HTML
<a-scene>
  <a-box color="red" position="0 2 -5" rotation="0 45 45" scale="2 2 2"></a-box>

  <!-- Out of the box environment! -->
  <a-entity environment="preset: forest; dressingAmount: 500"></a-entity>
</a-scene>
```
<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
