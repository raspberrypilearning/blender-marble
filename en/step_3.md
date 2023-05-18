## Add procedural textures

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Use **procedural textures** to design your marble material.
</div>
<div>
![The output of this step.](images/step3-output.png){:width="300px"}
</div>
</div>

--- task ---

Pull the material window up to give you a better view of the material settings:

![An animation of the material window being pulled up to reveal all of the material settings.](images/material-pull-up.gif)

**Tip:** Move your mouse to the edge of the window. The cursor will change to a double arrow. Click and drag the window up.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
A <span style="color: #0faeb0">**procedural texture**</span> is a texture that has been generated using a set of mathematical rules. Procedural textures are used to make high-quality, easily editable, scalable textures that can be added to any surface and still fit together perfectly at the edges.
</p>

### Create a Noise Texture

--- task ---

Go to **Add** > **Texture** and select **Noise Texture**:

![The Add menu open in the material window, with 'Texture' then 'Noise Texture' highlighted.](images/add-texture.png)

--- /task ---

--- task ---

Place your new **Noise Texture** box to the left of the **Principled BSDF** box:

![The Noise Texture box placed to the left of the Principled BSDF box in the material window.](images/texture-left.PNG)

**Tip**: The new Noise Texture box clings to your cursor until you have clicked it into place.

--- /task ---

--- task ---

Join the Noise Texture **Color** to the Principled BSDF **Base Color**:

![An animation of clicking and dragging from the dot next to the Color property in the Noise Texture box to the dot next to the Base Color property in the Principled BSDF box to create a join between them.](images/join.gif)

**Tip:** Click and drag from the dot next to **Color** to the dot next to **Base Color**.

--- /task ---

--- task ---

**Notice:** 👀 The material on the sphere has now changed:

![The sphere with a multicoloured effect.](images/colour-sphere.PNG)

--- /task ---

### Combine textures

--- task ---

A material can use more than one texture.

Go to **Add** > **Texture** and this time select **Musgrave Texture**:

![The Add menu open, with 'Texture' then 'Musgrave Texture' highlighted.](images/musgrave-texture.png)

--- /task ---

--- task ---

Place your new **Musgrave Texture** box to the left of the **Noise Texture** box:

![The Musgrave Texture box placed to the left of the Noise Texture box.](images/musgrave-left.png)

--- /task ---

--- task ---

Join the Musgrave Texture **Height** to the Noise Texture **Vector**:

![The Height property in the Musgrave Texture box joined to the Vector property in the Noise Texture box.](images/join-textures.png)

**Tip:** Click and drag from the dot next to **Height** to the dot next to **Vector**.

--- /task ---

--- task ---

**Notice:** 👀 The material on the sphere has changed again:

![The sphere with a new multicoloured effect.](images/musgrave-sphere.png)

--- /task ---

### Customise your material

--- task ---

Adjust the **Vector** settings in the **Musgrave Texture** and **Noise Texture** boxes until you are happy with the look of your marble:

![The Vector settings in the Musgrave Texture and Noise Texture boxes with example values.](images/vector-settings.png)

**Tip:** To change the setting values, hold the left mouse button down and drag your mouse to the left or right:

![An animation of clicking on a Vector setting and dragging to the left and right to increase and decrease the value.](images/drag.gif)

--- /task ---

--- save ---

