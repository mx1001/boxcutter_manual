
![header](img/banner.gif)

# Mode: Blue Box

Hotkey >> K (during draw)

Blue cut is for knife. When using this tool the geometry will be implied on the mesh. In order to see it you will have to enter edit mode or enable wire view in the 3d view. As of version 714 the wire will be shown during operation.

![mode](img/modes/m23.gif)

This mode is normally used to cleanup / prepare / optimize booleans or linework for bevels.

![mode](img/modes/m24.gif)

# Blue w/ Ngon Cyclic

When using ngon c will cycle cyclic. If you use this with knife you can cut lines into models and with wireframes showing you can efficiently clean up booleans.

> Having lines that don't converge with corners will result in smoother shading and a better result with the bevel modifier.

![mode](img/modes/m25.gif)

# Custom Grid Edit Mode cutting

In edit mode using a grid with **no faces** as the custom cutter in 2d will utilize knife project. This can be used to cut edges into models to help them deform easier.   

![mode](img/modes/m47.gif)

> After knife project cutting something like twist 360 can deform the object with array.

![mode](img/modes/m48.gif)

During this gif I did some additional steps.

- deleted faces at merge point (not faces only)
- mirror (symmetry) for making both sides the same
- twist 360 to make it a radial on the x-axis

# Knife box material delete

Due to the abnormal workflow that created the Blue box it isn't without glitches. For example when knife box is used the material could disappear.
We are aware of this issue and hope to fix it but in the meantime but for now you will need to reassign the material.

![faq](img/faq/f28.gif)

# Knife cut w/ mirror issues.

When knife cutting it might be needed to turn the mirror off temporarily.

Below you can see that in action.

![faq](img/faq/f8.gif)

> For some reason this only happens with the hardOps mirror at this time.

![faq](img/faq/f9.gif)

# Classic videos on Blue Box

Boxcutter 704 was the reintroduction of blue box in it's 3d form. This video shows me re-introducing the 2.8 version to users. It was the main focus of this video and should give some insight.

704 Enter Blue Box

<iframe width="560" height="315" src="https://www.youtube.com/embed/BJ7P2n1cAFY" frameborder="0" allowfullscreen></iframe>
