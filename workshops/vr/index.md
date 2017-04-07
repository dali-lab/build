---
layout: page
title: VR! On the Web!
published: true
---



WebVR is a new standard that is rapidly developing. We'll play with a few technologies and make a tiny world with some moving parts with Google Cardboard.

![obama vr](imgs/obama-vr.jpeg){: .small .fancy}


## Building Assets

What is a game without some cool environment and assets?  So first thing we'll play with building some stuff.

<iframe src='https://cartrdge.com/exmachina/voxel-seamonster/embed' frameborder='0' scrolling='no' width='640' height='360' allowfullscreen></iframe>

[magicavoxel]: https://ephtracy.github.io/

[MagicaVoxel][magicavoxel] is a free and user-friendly tool for building
3D scenes and models using *voxels* (i.e., blocks). MagicaVoxel makes modeling super
easy, similar to building in Minecraft.

![magicavoxel](https://i.imgur.com/XYYXjIn.jpg){: .medium .fancy}

## Installation

🚀 MagicaVoxel works on Windows and OS X. On the [MagicaVoxel
homepage][magicavoxel], click the *Download* button and install the application:

![magicavoxel install](https://i.imgur.com/GmgdyHs.jpg){: .medium .fancy}

On macOS, open the MagicVoxel app file by clicking on it in Finder. Initially,
you will see a message noting that you cannot open applications from
unidentified developers. After dismissing that message, open the
*Security & Privacy* settings pane and click "Open Anyway" on the MagicVoxel app:

![osx security](http://i.imgur.com/DAsjv4F.png){: .medium_small .fancy}

Alternatively, you can find the MagicVoxel app file in Finder, right click on it,
and then choose "Open" from the shortcut menu. In the subsequent dialogue
click "Open" again. For more information, visit [Apple's documentation](https://support.apple.com/kb/PH25088?locale=en_US) on unidentified developers.

## Tutorial

The official tutorial video serves as a good introduction to using MagicaVoxel.
The author quickly runs through many basic features in 10 minutes:

<iframe width="560" height="315" src="https://www.youtube.com/embed/PPu7SJ1_bwc" frameborder="0" allowfullscreen></iframe>

🚀 The best way to learn the MagicaVoxel UI is to click around, play with application controls,
and pay attention to the tooltips on hover. Many developers are able to create their first
scene within a half hour!  Given the absence of official tutorials, however,
the following serves as a quick guide to navigating the UI.

### Viewport

The center panel hosts the viewport where we build our model. We can change the
viewport our mouse/trackpad or the `wasd` keys:

- **Pan**: Hold `<space> + <right-click>` and move the mouse or trackpad, or
  hold `<space>` and press one of the `<a>` or `<d>` keys.
- **Rotate**: Hold `<right-click>` and move the mouse or trackpad, or press one
  of the `<a>` or `<d>` keys.
- **Zoom**: Scroll up and down with the mouse or trackpad, or press one of the
  `<w>` or `<s>` keys.

![magicavoxel viewport](http://imgur.com/vq34Mkk.jpg){: .medium .fancy}

The top right corner of the viewport allows you to change the bounding dimensions
of the model. Note that in MagicaVoxel, the XY plane is horizontal and the Z
axis points up.

### Color Palette

The left panel is the color palette. You can use the default palettes,
modify them, create your own, and save them. The palette is tied to the scene
so if you change from the palette a color that a voxel is using, the voxel will
update its color. At the bottom, there are tools to define your own color with
sliders or via copying and pasting hex or rgb values:

![magicavoxel color palette](https://i.imgur.com/vq34Mkk.jpg){: .medium .fancy}

### Brushes

The brushes panel is to the right of the color palette. Brushes add, erase, or
paint voxels in various shapes, sizes, and patterns. With a brush selected,
simply click in the viewport on your model to use it:

![magicavoxel brushes](https://i.imgur.com/pqrUAFT.gif){: .medium .fancy}

There are six brushes:

- **V (Voxel)**: Works on individual or discrete groups of voxels.
- **F (Face)**: Works on groups of adjacent voxels that are the same shape or color.
- **B (Box)**: Works on a 2-dimensional box of voxels where we control the area
  of the box by dragging.
- **L (Line)**: Works on a 1-dimensional line of voxels where we control the
  length of the line by dragging.
- **C (Center)**: Works on a circle or square of voxels where we control the
  radius of the shape by dragging.
- **P (Pattern)**: The pattern brush lets us use other MagicaVoxel models and paste them
  into the current model. Useful for placing repeated shapes.

### Actions

There are four actions that work in conjunction with the brush type:

- **Attach (t)**: Add voxel(s).
- **Erase (r)**: Remove voxel(s).
- **Paint (g)**: Change color of existing voxel(s).
- **Move**: Moves entire model. Unfortunately, there is no way to select
  individual voxel(s) to move.

![magicavoxel actions](https://i.imgur.com/uLQcQrT.gif){: .medium .fancy}

Below the actions are three color picking tools to pick, remove, and place
color. It is useful to know the `<alt> + <click>` shortcut to select a color by
clicking on a voxel.

## Make Something

Now that you have some idea of how to use MagicaVoxel try making something, or preload a model and alter it!

![](imgs/sword-char.jpg){: .medium .fancy}


## Export Your Creation

When you are ready, export your amazing creation to `Obj` format - save it somewhere you can find. This will generate 3 files for you.  

* `.obj` is the 3D object as a set of vertices and faces
* `.mtl` is the material for the object, and contains how the texture should map to the surface of your object
* `.png` is the texture, in this case an image with lots of different color corresponding to the colors of the voxels.

![](imgs/export.jpg){: .medium .fancy}



# PlayCanvas

Now we want to share our work with the world and put it into a VR environment!

[pc]: http://playcanvas.com


One way to do that is to use [PlayCanvas][pc].  [PlayCanvas][pc] is a full featured 2d/3d game engine for creating interactive content for the web.  They recently added WebVR support and will do very nicely for our purposes.

<iframe src="https://s3-eu-west-1.amazonaws.com/apps.playcanvas.com/Ppfa6E7q/index.html" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen="true" allowvr="" width="640" height="360" id="playcanv"></iframe>

🚀 Go create an account now (free)!

🚀 PlayCanvas allows you to remix other public projects. Let's **Fork** our [VR starter project](https://playcanvas.com/project/473127/overview/dali-tutorial).








#### References

* MagicaVoxel section remixed from [aframe.io](https://aframe.io/docs/0.5.0/guides/building-with-magicavoxel.html), aframe is another WebVR platform that is up and coming. It isn't as full featured of a game engine as PlayCanvas though.
* PlayCanvas [Manual](http://developer.playcanvas.com/en/user-manual/vr/)
