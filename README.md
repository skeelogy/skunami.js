skunami.js
==========

### Introduction

This is a collection of JavaScript / GLSL height field water libraries for Three.js plane meshes.

### Available Height Field Water Types

* **Pipe Model** _("Fast Hydraulic Erosion Simulation and Visualization on GPU", Xing Mei, Philippe Decaudin and Bao-Gang Hu, Pacific Graphics 2007)_
* **X Water** _(["2D Water", Hugo Elias](http://freespace.virgin.net/hugo.elias/graphics/x_water.htm))_
* **Mueller GDC 2008** _("Fast Water Simulation for Games Using Height Fields", Matthias Mueller-Fisher, Game Developers Conference 2008)_
* **Mueller GDC 2008 Hello World** _("Fast Water Simulation for Games Using Height Fields", Matthias Mueller-Fisher, Game Developers Conference 2008)_
* **Tessendorf iWave** _("Interactive Water Surfaces", Jerry Tessendorf, Game Programming Gems 4)_

### Features

* GPU-based height field water simulation for fast performances on high resolution meshes
* Different types of user interaction with the water: source, sink, disturb
* Water ripples reflect off terrain and static obstacles
* Two-way coupling with dynamic rigid body objects i.e. water makes objects float while objects create ripples on water after displacing it
* `SKUNAMI.GpuPipeModelWater` is able to accumulate behind terrains and static obstacles

### Examples

**1) Water Types** [[Demo](http://skeelogy.github.io/skunami.js/examples/skunami_waterTypes.html)]

&nbsp;&nbsp;&nbsp;[![ScreenShot](http://skeelogy.github.io/skunami.js/screenshots/video_skunami_waterTypes.jpg)](http://www.youtube.com/watch?v=yj3jrXWwqyU)

* Different water types and their behaviour upon user interaction
* Flooding control to change water level

**2) Obstacles** [[Demo](http://skeelogy.github.io/skunami.js/examples/skunami_twoWayCoupling.html)]

&nbsp;&nbsp;&nbsp;[![ScreenShot](http://skeelogy.github.io/skunami.js/screenshots/video_skunami_obstacles.jpg)](http://www.youtube.com/watch?v=yEbXhAY9qao)

* Reflection of water ripples that bounce into terrain and static obstacles
* Accumulation of water behind terrain and static obstacles

**3) Two-Way Coupling With Dynamic Rigid Bodies** [[Demo](http://skeelogy.github.io/skunami.js/examples/skunami_twoWayCoupling.html)]

&nbsp;&nbsp;&nbsp;[![ScreenShot](http://skeelogy.github.io/skunami.js/screenshots/video_skunami_twoWayCoupling.jpg)](http://www.youtube.com/watch?v=f_6aTwP2lMg)

* Dynamic objects (and terrain) cause ripples on water after displacing it
* Water makes the dynamic objects float

### Documentation

* [1.0.x](http://skeelogy.github.io/skunami.js/docs/1.0.x)

### Browser Support

Tested only in Google Chrome (recommended) and Mozilla FireFox

### License

Released under The MIT License (MIT)<br/>
Copyright (c) 2013 Skeel Lee ([http://cg.skeelogy.com](http://cg.skeelogy.com))
