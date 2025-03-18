# 01-Workit-Landing-Page

Workit Landing Page

Here's what I learned:

To make a circle make sure the width and height are the same as it is on figma.

Curved bottom:
clip-path: ellipse(100% 100% at 50% 0%);
ellipse(100% 50%) → Creates an ellipse that spans 100% of the width and 50% of the height.

at 50% 0% → Positions the ellipse at the top center (0% Y-axis), ensuring the curve appears at the bottom of the element.

To put an image on top of the ellipse I had to create an element outside of its container. I then did position absolute and centered it.
