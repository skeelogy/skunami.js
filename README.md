skunami.js
==========

### Introduction

This is a collection of JavaScript/GLSL height field water libraries for Three.js plane meshes.

### Available Height Field Water Types

* **Pipe Model** _("Fast Hydraulic Erosion Simulation and Visualization on GPU", Xing Mei, Philippe Decaudin and Bao-Gang Hu, Pacific Graphics 2007)_
* **X Water** _(["2D Water", Hugo Elias](http://freespace.virgin.net/hugo.elias/graphics/x_water.htm))_
* **Muller GDC 2008** _("Fast Water Simulation for Games Using Height Fields", Matthias Mueller-Fisher, Game Developers Conference 2008)_
* **Muller GDC 2008 Hello World** _("Fast Water Simulation for Games Using Height Fields", Matthias Mueller-Fisher, Game Developers Conference 2008)_
* **Tessendorf iWave** _("Interactive Water Surfaces", Jerry Tessendorf, Game Programming Gems 4)_

### Features

* GPU-based height field water simulation for fast performances on high resolution meshes
* Different types of user interaction with the water: source, sink, disturb
* Water ripples reflect off terrain and static obstacles
* Dual-coupling with rigid body objects i.e. water makes objects float while objects create ripples on water
* `SKUNAMI.GpuPipeModelWater` is able to accumulate behind terrains and obstacles

### Examples

* [Water Types](http://skeelogy.github.io/skunami.js/examples/skunami_waterTypes.html)

### Documentation

* [1.0](http://skeelogy.github.io/skunami.js/docs/1.0)

### License

Released under The MIT License (MIT)<br/>
Copyright (c) 2013 Skeel Lee ([http://cg.skeelogy.com](http://cg.skeelogy.com)) @skeelogy
