![header](img/banner.gif)

# Mode: Extract

Hotkey >> Y (during draw)

Extract is a shape capable of taking other shapes and using them as the custom cutter.
The purpose of this shape is to take areas then allow users to reuse them.

![mode](img/modes/m26.gif)

A few things to note:

- extract **only works with live booleans** (if the mesh is applied it will not work)
- requires the rotation be 0ed out (gets strange with transformations)

# Using active Only as a jumpoff point

Active only seems useless however not being able to cut the secondary selection and instead use it for obtaining orientation is a powerful feature.

![mode](img/modes/m27.gif)

I used object scroll from hardOps to get the cutter for the main cylinder that I used to orient my extraction to. I tend to start in red just to see what I'm going to take disappear and then press Y to toggle before application to extract.

# Classic extraction w/ hardOps and grey

When it comes to taking things that are not live and doing the whole extraction process manually it is possible using hardOps as a secondary.

![mode](img/modes/m28.gif)

> drew a make circle after trying to use the center point of the X but I turned off vert snap
> when adding a boolean with Q I preesed shift to keep the shape live. And not mess with the main shape.


Some areas can be tricky to extract so you have to think about it subtractively. However this backup exists as an idea on how to take an area until we add it.
