## Add a texture

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Design and add a texture to your marble.
</div>
<div>
![Step three output.](images/step3-output.png){:width="300px"}
</div>
</div>

--- task ---

Pull up the material window to give you a better view of the material settings. 

![The materials pane is pulled up to reveal all of the material settings.](images/material-pull-up.gif)

**Tip**: Move your mouse the the edge of the window until the mouse pointer changes to a double arrow. Click and drag the window up. 

--- /task ---

### Create a Noise texture

--- task ---

Go to 'Add' > 'Texture' and select 'Noise Texture'.

![A texture is added using 'Add' > 'Texture' menu.](images/add-texture.png)

--- /task ---

--- task ---

Place your new Noise texture window to the left of the 'Principled BSDF' box. 

![The 'Noise Texture' box has been placed to the left of the 'Principled BSDF' box.](images/texture-left.PNG)

**Tip**: The new Noise texture window clings to your mouse until you have clicked it into place.

--- /task ---

--- task ---

Join the Noise texture **Color** to the **Base color** of the Principled BSDF.

![A short animation showing the 'Color' property in the Texture box being dragged to join the 'Base color' property in the Principled BSDF box.](images/join.gif)

**Tip**: Click and drag from the dot next to 'Color' to the dot next to 'Base color'.

--- /task ---

--- task ---

Notice 👀 that the material on the sphere has now changed. 

![A multi-coloured effect has been added to the sphere.](images/colour-sphere.PNG)

--- /task ---

### Combine textures

--- task ---

A material can use more than one texture. 

Go to 'Add' > 'Texture' and this time select 'Musgrave Texture'.

![The vector settings on the 'Texture' box are highlighted.](images/vector-settings.png)

--- /task ---

--- task ---

Place your new Musgrave texture window to the left of the 'Noise texture' box. 

![The 'Noise Texture' box has been placed to the left of the 'Principled BSDF' box.](images/texture-left.PNG)

--- /task ---

--- task ---

Join the Musgrave texture **Height** to the **Vctor** of the Noise texture.

![A short animation showing the 'Color' property in the Texture box being dragged to join the 'Base color' property in the Principled BSDF box.](images/join.gif)

**Tip**: Click and drag from the dot next to 'Height' to the dot next to 'Vector'.

--- /task ---

### Customise your material

--- task ---

Adjust the Vector settings in the Musgrave and Noise textures until you are happy with the look of your marble. 

![The vector settings on the 'Texture' box are highlighted.](images/vector-settings.png)

**Tip**: You can drag your mouse from left to right on each value to slide the values and select smaller or larger numbers.

![The mouse is used to drag the vector settings from left to right and increase or decrease the value.](images/drag.gif)

--- /task ---

--- save ---

