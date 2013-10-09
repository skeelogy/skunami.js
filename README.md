skunami-cpu.js
==============

## NOTE: This is an experimental CPU version which is quite slow and is not actively maintained / supported. Please use the GPU version from the master branch if you need an interactive height field water library.

### Introduction

This is a collection of JavaScript height field water libraries for Three.js plane meshes.

### Available Height Field Water Types

* **Pipe Model** _("Fast Hydraulic Erosion Simulation and Visualization on GPU", Xing Mei, Philippe Decaudin and Bao-Gang Hu, Pacific Graphics 2007)_
* **X Water** _(["2D Water", Hugo Elias](http://freespace.virgin.net/hugo.elias/graphics/x_water.htm))_
* **Mueller GDC 2008** _("Fast Water Simulation for Games Using Height Fields", Matthias Mueller-Fisher, Game Developers Conference 2008)_
* **Mueller GDC 2008 Hello World** _("Fast Water Simulation for Games Using Height Fields", Matthias Mueller-Fisher, Game Developers Conference 2008)_
* **Tessendorf iWave** _("Interactive Water Surfaces", Jerry Tessendorf, Game Programming Gems 4)_

### Features

* Different types of user interaction with the water: source, sink, disturb
* Water ripples reflect off terrain and static obstacles
* Two-way coupling with dynamic rigid body objects i.e. water makes objects float while objects create ripples on water after displacing it
* `SKUNAMICPU.PipeModelWater` is able to accumulate behind terrains and static obstacles

### License

Released under The MIT License (MIT)<br/>
Copyright (c) 2013 Skeel Lee ([http://cg.skeelogy.com](http://cg.skeelogy.com))
