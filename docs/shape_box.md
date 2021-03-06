![header](img/banner.gif)

# Shape: Box

I used to say box was all I needed. I have a fondness for the box but let's keep it formal.

Box does just what the name entails. It draws a box. Corner draw by default.

First is the draw. and then the extrude. Click and let go and click to apply.

![mode](img/shape/s1.gif)

> You can draw and extrude or you can draw click and just lazorcut through the model.

# Wire / Solid Drawing Toggle

Pressing H during draw will use wire instead of solid.

![mode](img/shape/s52.gif)

# Center, Corner and Uniform Draw

For this to work the following prefs must be enabled. They are on by default and should only be off if your keymap is so odd that it is unable to be explained.

![mode](img/shape/s13.png)

During draw the following draw modifiers apply:

- alt for uniform draw
- shift for center draw (where the box is the same on all sides)
- alt + shift for center uniform draw (how the cube center was cut evenly)

Here you can see them in action.

![mode](img/shape/s14.gif)

# Modes

- [cut](mode_red.md)
- [slice](mode_yellow.md)
- [join](mode_green.md)
- [knife](mode_blue.md)
- [make](mode_grey.md)
- [extract](mode_black.md)

![mode](img/shape/s10.gif)

> Since extractions changes over to simple shape that is why the shape transitioned over to custom.

# Box Operations

Box can be started with any of the Operations:

- array
- solidify
- bevel
- mirror

To show them all in action:

![mode](img/shape/s9.gif)

# Repeat

Ctrl + double clicking will repeat the last operation. With fade now the shapes stay behind longer depending on fade time.

![mode](img/shape/s26.gif)

You can repeat a variety of things even custom shapes.

![mode](img/shape/s27.gif)

Repeat can also be used with shift to live in order to adjust the repeated shape post operation.

![mode](img/shape/s28.gif)

> with shift to active not on the repeat to live selected the main object as well which is more clicking to deselect.

# Rotate Shape During draw

Pressing R or ~ (tilda) will rotate the shape (alt + scroll) 90 degrees.

![mode](img/shape/s51.gif)

# Shape Recall

> Do not try to recall shapes that do not exist.

When drawing a box or circle you can recall previous cutters in the cutter collection with alt + MMB or the C key.

Shape recall only works with Box, and circle. Ngon will have a special solution for recall.

![mode](img/shape/s49.gif)

![mode](img/shape/s50.gif)


# Orientation

When an object is selected the default orientation should be object.

![mode](img/shape/s2.png)

![mode](img/shape/s4.png)

![mode](img/shape/s5.png)

> The alternative is world and cursor.

# What is lazorcut?

Lazorcut is cutting without an extrude. It can either be done manually or with quick execute from the behavior panel.

> Quick Execute should definetely not be on by default.

![mode](img/shape/s3.gif)

# View Aligned cutting

This topbar button toggles view align cutting.

![mode](img/shape/s6.gif)

When it is on the box is draw from the view and not from the surface / cursor / world.

![mode](img/shape/s7.gif)

> View align is a throwback to our classic 2.7x beginnings.

# 2d vs 3d Box

Previously we talked about this button.

![mode](img/shape/s6.gif)

When it comes to [knife](mode_blue.md) this button is a little more special.

In 2.8 we attempted to make a 3d blue box and sometimes it can have issues with the goal we intended for it. As a result the above button also toggle classic and new blue box.

New blue box is 3d and nice when its working right.

![mode](img/shape/s31.gif)

But it runs the risk of interior face creation.

![mode](img/shape/s32.gif)

> And no one wants faces on the inside of their model.

So as a result classic blue box is back. But only in 2d form. Like classic.
It can be activated in 2d view when you draw starting **off of the mesh**.

![mode](img/shape/s33.gif)

With view align on the classic blue box will always be active. Across all shapes.

![mode](img/shape/s34.gif)

# View align snap dot gotcha

When view align is on and you aren't aware the snapping dots on ctrl will behave differently.

This can be annoying until you realize view align up top is active. Just something to be aware of.

![mode](img/shape/s8.gif)

# Edit Mode Box

While being typically used in object mode. Box can also be used in edit mode with most of the shapes.

> In edit mode you may have to start boxcutter with alt + W or use the T panel icon

![mode](img/shape/s17.gif)

A few additional notes:

- users can even draw destructively in edit mode then shift to live to modify the shape in object mode.
- most of the shapes work but some are still in a state of repair but red box works
- edit mode boxcutter usually starts you in blue box so you can cut linework

# Wire Draw Type

During draw you can press H to show wire. This can come in handy if you need the absence of color for a moment. Or forever.

![mode](img/shape/s11.gif)

These are the preferences for setting the default for this behavior and the thickness of the lines.

![mode](img/shape/s12.png)

# Box and snapping

see [snapping](snapping.md)
