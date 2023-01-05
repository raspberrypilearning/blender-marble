## Add procedural textures

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Use **procedural textures** to design your marble material.
</div>
<div>
![Step three output.](images/step3-output.png){:width="300px"}
</div>
</div>

--- task ---

Pull up the material window to give you a better view of the material settings:

![The materials pane is pulled up to reveal all of the material settings.](images/material-pull-up.gif)

**Tip**: Move your mouse the the edge of the window. The mouse pointer will change to a double arrow. Click and drag the window up. 

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
A <span style="color: #0faeb0">**procedural texture**</span> is a texture that has been generated using a set of mathematical rules. Procedural textures are used to make high quality, easily editable, scalable textures that can be added to any surface and still fit together perfectly at the edges. 
</p>

### Create a Noise texture

--- task ---

Go to 'Add' -> 'Texture' and select 'Noise Texture':

![A texture is added using 'Add' > 'Texture' menu.](images/add-texture.png)

--- /task ---

--- task ---

Place your new **Noise texture** window to the left of the 'Principled BSDF' box:

![The 'Noise Texture' box has been placed to the left of the 'Principled BSDF' box.](images/texture-left.PNG)

**Tip**: The new Noise texture window clings to your mouse until you have clicked it into place.

--- /task ---

--- task ---

Join the **Noise texture** 'Color' to the **Principled BSDF** 'Base color':

![A short animation showing the 'Color' property in the Texture box being dragged to join the 'Base color' property in the Principled BSDF box.](images/join.gif)

**Tip**: Click and drag from the dot next to 'Color' to the dot next to 'Base color'.

--- /task ---

--- task ---

Notice 👀 that the material on the sphere has now changed:

![A multi-coloured effect has been added to the sphere.](images/colour-sphere.PNG)

--- /task ---

### Combine textures

--- task ---

A material can use more than one texture. 

Go to 'Add' -> 'Texture' and this time select 'Musgrave Texture':

![A texture is added using 'Add' > 'Texture' menu.](images/musgrave-texture.png)

--- /task ---

--- task ---

Place your new **Musgrave texture** window to the left of the **Noise texture** box:

![The 'Musgrave Texture' box has been placed to the left of the 'Noise texture' box.](images/musgrave-left.png)

--- /task ---

--- task ---

Join the **Musgrave texture** 'Height' to the **Noise Texture** 'Vector':

![The 'Height' property in the Musgrave Texture box has been dragged to join the 'Vector' property in the Noise texture box.](images/join-textures.png)

**Tip**: Click and drag from the dot next to 'Height' to the dot next to 'Vector'.

--- /task ---

--- task ---

Notice 👀 that the material on the sphere has again changed:

![A new multi-coloured effect has been added to the sphere.](images/musgrave-sphere.png)

--- /task ---

### Customise your material

--- task ---

Adjust the 'Vector' settings in the **Musgrave Texture** and **Noise texture** until you are happy with the look of your marble:

![The vector settings on the 'Texture' box are highlighted.](images/vector-settings.png)

**Tip**: To change the setting values, hold the left-mouse button down and drag your mouse to the left or right:

![The mouse is used to drag the vector settings from left to right and increase or decrease the value.](images/drag.gif)

--- /task ---

--- save ---

