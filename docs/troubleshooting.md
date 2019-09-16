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
