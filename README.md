# 3d-many-viewports

Simple 3d model with multiple Viewports rendered on a Sprite in godot 3.0

# Using Viewport:

* make sure a camera is attached to the viewport ( the Camera is a child of the Viewport).
* create a Control node to draw the images of the viewports by adding a Sprite and setting the Sprite's texture in the editor to ViewportTexture.

# 2D view
After creating the viewports the Sprite nodes have to be positioned on the 2d Control node.

# 3D view
Put in any 3d model, add viewports with a camera anywhere you want.

# Script

no gdscript is required

# I don't know

Why there are so many errors in the debugger tab and it still works, why the texture from the viewport is seemingly rendered upside down.
