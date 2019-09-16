![header](img/banner.gif)

## Troubleshooting

Issues are bound to occur when using Booleans and concept modelling workflows. There are support tools across hardOps and boxCutter for making the process easier.

# Why does my bevel look weird?

First, let's check face orientation.

![troubleshooting](img/troubleshooting/ts1.gif)

Sometimes a shape can come in with the normals flipped. In 2.8 this can be harder to see. With the hardOps
alt + V submenu users can view the shading to find the red.

Notice how when the normals are flipped things behave as expected.

> shift + N in edit mode with everything selected flips normals

![troubleshooting](img/troubleshooting/ts2.gif)

When the normals are all blue things will behave as expected.

![troubleshooting](img/troubleshooting/ts3.gif)

Face orientation is located in the viewport area of the 3d view.
![troubleshooting](img/troubleshooting/ts4.gif)

# Why did my extraction fail?

Extractions can be strict at this moment with the following rules:
- extract only takes live Booleans
- extract only works on meshes with applied rotation / scale / location

This is typically how extraction can behave.

![troubleshooting](img/troubleshooting/ts5.gif)

Notice how troublesome extractions get with unapplied rotation.

![troubleshooting](img/troubleshooting/ts6.gif)

Once rotation is applied it behaves a little better.

![troubleshooting](img/troubleshooting/ts7.gif)

# Why are my bevels skewed?

Depending on the geometry supplied bevels can show incorrectly.

Here we'll set up a few booleans and then bevel it.

![troubleshooting](img/troubleshooting/ts8.gif)

By viewing the wires we can see what is going on.

![troubleshooting](img/troubleshooting/ts9.gif)

[Blue box](mode_blue.md) is capable of fixing it. By adding an edge the bevel is able to better deal with the boolean.

![troubleshooting](img/troubleshooting/ts10.gif)

# How would you fix this shape?

![troubleshooting](img/troubleshooting/ts12.png)

To first create the situation.

![troubleshooting](img/troubleshooting/ts11.gif)

We could solve this by using:
- mirror
- bevel (3 segements / profile 1)
- isolation loops

![troubleshooting](img/troubleshooting/ts13.gif)

And to fix the bottom.

![troubleshooting](img/troubleshooting/ts14.gif)

Without the solving of the area to relax the bevel it shades differently. You can also cleanup to a minimal amount and get away with it but getting it right allows for close-ups and less visual artifacting.

![troubleshooting](img/troubleshooting/ts15.gif)

It can require some finessing to get both the form and the bevel to be guided properly by the flow. However this isn't possible non-destructively at this time. 
