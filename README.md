# AR.js-examples

Examples using the AR.js library

The goal of this collection is to provide a set of basic and instructive examples that introduce the various features in the Javascript-based Augmented Reality (AR) library, AR.js (version 2), built upon the <a href="https://aframe.io/">A-Frame</a> and <a href="https://threejs.org/">three.js</a> libraries.

Viewing the AR examples will require a device with a camera and various marker images to be detected, which are available in the <code>markers</code> directory in this repository. Requires the kanji marker unless otherwise specified.

<hr/>

<table class="item-container"><tr>
	<td><a href="basic.html"><img src="demos/basic.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="basic.html">Hello, AR World!</a>
	<p>A basic scene that places plain and textured shapes on markers (kanji, barcodes 0/1/2).</p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="models.html"><img src="demos/model.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="models.html">3D model</a>
	<p>A single gltf model attached to a marker.</p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="cubemap.html"><img src="demos/cubemap.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="cubemap.html">Multi-Textured Cube</a>
	<p>A cube with different images on each side, attached to a marker. <br/>Uses the aframe-multisrc component.</p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="animation.html"><img src="demos/animation.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="animation.html">Animation</a>
	<p>Animating (rotating) a globe attached to a marker, using the built-in animation component.</p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="text.html"><img src="demos/text.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="text.html">Text (2D and 3D)</a>
	<p>Attaching text to the kanji and hiro markers.<br/>
	3D text uses the aframe-text-geometry component.</p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="particles.html"><img src="demos/particles.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="particles.html">Particle Effects</a>
	<p>Creating a particle system effect, attached to a marker. 
		<br/>Uses the aframe-particle system component.</p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="scripting.html"><img src="demos/scripting.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="scripting.html">Introduction to Scripting</a>
	<p>Rotates a globe attached to a marker, by writing an A-Frame component and modifying the underlying Three.js object.</p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="canvas.html"><img src="demos/canvas.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="canvas.html">Canvas Textures</a>
	<p>Using an HTML canvas as the texture for a cube; creating an animation ("bouncing block") on the canvas and updating the cube texture. </p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="detection.html"><img src="demos/detection.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="detection.html">Detection</a>
	<p>A cube is attached to a kanji marker. Red, yellow, and blue squares are attached to barcode markers 0, 1, and 2. 
	The color of the cube changes depending on which combination of the markers is visible.</p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="follower.html"><img src="demos/follower.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="follower.html">Persistence and Following </a>
	<p>A green square is attached to a marker. If the marker is no longer visible, the square turns red and remains in the last known
	position of the marker. If the marker then becomes visible again, the square turns green and moves (lerps) to the new position.</p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="line.html"><img src="demos/line.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="line.html">Line between two markers</a>
	<p>Drawing a line between the centers of barcode markers 0 and 1. (Updates line geometry vertices.)</p></td>
</tr></table>

<table class="item-container"><tr>
	<td><a href="line2.html"><img src="demos/cylinder.png" class="item-container-image" /></a></td>
	<td class="tableText"><a href="line2.html">Cylinder between two markers</a>
	<p>Since lines can be difficult to see, drawing spheres at the centers of barcode markers 0 and 1, and creating a cylinder between the them. (Reorients and rescales the cylinder depending on the distance between the markers.)</p></td>
</tr></table>

<!-- ### Demos

#### Hello, AR World! 
![demo](demos/basic.png)
#### 3D model 
![demo](demos/model.png)
#### Multi-Textured Cube 
![demo](demos/cubemap.png)
#### Animation 
![demo](demos/animation.png)
#### Text (2D and 3D)
![demo](demos/text.png)
#### Particle Effects 
![demo](demos/particles.png)
#### Introduction to Scripting 
![demo](demos/scripting.png)
#### Canvas Textures 
![demo](demos/canvas.png)
#### Detection
![demo](demos/detection.png)
#### Persistence and Following
![demo](demos/follower.png)
#### Line between two markers 
![demo](demos/line.png)
#### Cylinder between two markers
![demo](demos/cylinder.png)

 -->
