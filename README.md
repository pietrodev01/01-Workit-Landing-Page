# 01-Workit-Landing-Page

Workit Landing Page

Here's what I learned:

To make a circle make sure the width and height are the same as it is on figma and use border radius.

Curved bottom:
clip-path: ellipse(100% 100% at top);
ellipse(100% 100%) → Creates an ellipse that spans 100% of the width and 100% of the height of the element

at top → cuts the ellipse at the top of the element with the ellipse on the bottom

To put an image on top of the ellipse I had to create an element outside of its container. I then did position absolute and centered it.

On the desktop version I set the width of the photo to a vw value so it is responsive with width (calc(25vw + 20vh)). I set the value of left of the img container to a vw value as well so its container is responsive with width.

![screenshot](screenshot-1.png)
