## Create a marble 

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Create a marble using a **UV sphere** object. Add a new material to the sphere.
</div>
<div>
![The output of step 2.](images/step2-output.PNG){:width="300px"}
</div>
</div>

### Set up your project

--- task ---

Open Blender. Click outside the **splash screen** to close it: 

![Splash screen popup.](images/splash-screen.png)

A **Cube** object has been created for you. The cube has an orange outline to show it is the selected object:

![A 3D cube shown in the Object view. The Cube object is also highlighted in the Scene Collection window.](images/starter-cube.png)

--- /task ---

--- task ---

Click on the **Cube** and press **<kbd>Delete</kbd>** on your keyboard. This will give you an empty document to add in your sphere:

![The Blender environment is now empty because the cube has been deleted.](images/no-cube.PNG)

**Tip**: You can also right-click on the cube and choose 'Delete' to delete the cube.

--- /task ---

--- task ---

For this project, you need to enable the **Node Wrangler**. 

Go to the 'Edit' menu then choose 'Preferences'.

Now select 'Add-ons' and search for `node`.

Tick the box next to 'Node: Node Wrangler' then close the Preferences window:

![The Blender Preferences window with the 'Node: Node Wrangler' box ticked.](images/node-wrangler.png)

--- /task ---

### Create a marble

--- task ---

Add a new **UV Sphere** by going to 'Add' -> 'Mesh' -> 'UV Sphere':

![The add menu in Blender with Mesh and UV Sphere highlighted.](images/add-uv-sphere.png)

**Tip**: The icons in Blender are very small. Hover over them with your mouse to see a tool tip with the name of the tool. 

--- /task ---

--- task ---

With the **Sphere** selected, go to the 'Material Properties' tab. Click 'New' to add a new material to your sphere:

![A screenshot showing the Material Properties tab and the New button highlighted.](images/new-material-property.png)

**Tip**: A selected object has an orange outline.

--- /task ---

### Open the Shading editor

--- task ---

The Blender 'Shading editor' is used to design and view materials. 

Go to the menu at the top of the screen and choose 'Shading'. This will open the Shading editor:

![An arrow points to the 'Shading' menu option at the top of the screen. The view has changed to the shading editor.](images/shading-layout.png)

--- /task ---

--- task ---

To make it easier to focus on your material. Go to the 'Viewport Shading' dropdown. Change the 'World Opacity' to `0`:

![The 'Viewport Shading' dropdown has been selected and the 'World Opacity' has been changed to 0.](images/viewport-shading.png)

--- /task ---

--- task ---

To see the shading effect, adjust the view of your sphere so that it is 🔎 zoomed in and 🔄 rotated up slightly:

![The sphere is larger and rotated up.](images/step2-output.PNG)

--- collapse ---
---
title: Zoom and rotate in Blender
---

**Tip:** To navigate Blender using a computer mouse with a middle scroll button:
+ Hold the middle-button down and drag the mouse around to rotate the view
+ Scroll the middle-button forward and backward to zoom in and out of the view

![An animation showing the view rotating around the sphere and zooming in and out.](images/mouse-nav.gif)

**Tip:** If you do not have a computer mouse with a middle-button you can use the navigation icons. Place the mouse over the **zoom** or **move** icons to see the cursor change to 4 arrows. Hold the left mouse button down then drag the mouse around to change the view. 

![An animation showing the navigation icons being used to zoom in and out and rotate around the sphere.](images/menu-nav.gif)

--- /collapse ---

--- /task ---

--- task ---

Go to 'File' -> 'Save As' and save your file as 'marble.blend':

![The Save As window with the filename and 'Save As' buttons highlighted.](images/save-as.png)

**Tip:** You can reopen a saved Blender project using ‘File’ -> ‘Open’.

--- /task ---


