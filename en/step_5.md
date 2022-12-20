## Create an image of your texture

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Create an image of your **texture** so that you can use it with other objects and projects.
</div>
<div>
![Output of step 5.](images/step5-output.png){:width="300px"}
</div>
</div>

### Create a blank image

--- task ---

Go to the 'Image Viewer' menu in the bottom-left of the Shading editor. Click on '+ New' and give your image a sensible name like `MyTexture`.

Click OK and the area will become black. 

![A screenshot of the Image Viewer menu with the '+ New' section highlighted. Arrows point to the filename area and the OK button.](images/image-viewer.png)

--- /task ---

--- task ---

**Add** a new **Image Texture** by going to 'Add' > 'Texture' > 'Image Texture'.

![A screenshot of the Add menu. Texture and Image Texture are highlighted.](images/image-texture.png)

--- /task ---

--- task ---

Place the 'Image Texture' box away from your other boxes.

![A screenshot showing the 'Image Texture' box place away from the other boxes on the screen.](images/place-texture.png)

--- /task ---

--- task ---

Go to your new Image Texture box and click on the 'Browse Image' icon. 

Select the image that you just created. You may have named this `MyTexture`.

![A screenshot showing the 'Browse Image' icon with the 'MyTexture' image selected.](images/add-mytexture.png)

--- /task ---

### Bake your material onto the image

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Texture baking**</span> is the process of taking complex surface data from a 3D object and saving it to a 2D texture image. The image can then be used on another 3D object or even exported to be used in another software.

![A strip of images showing a texture on a sphere then as a flat image and then transferred to cube, cylinder, and cone objects.](images/render-engine.png)
</p>

--- task ---

Go to the 'Render Properties' tab on the right-hand side. 

To allow baking, change the 'Render Engine' to 'Cycles'.

![A screenshot showing the 'Render Properties' tab and the 'Render Engine' option being changed to 'Cycles'.](images/render-engine.png)

--- /task ---

--- task ---

The most common type of baking used to create textures is **Diffuse baking**. 

Expand the 'Bake' menu in the 'Render Properties' tab and change the 'Bake Type' to 'Diffuse'.

![A screenshot showing the 'Bake' section of the 'Render Engine' and the 'Bake Type' being changed to 'Diffuse'.](images/diffuse-bake.png)

--- /task ---

--- task ---

In the 'Bake' menu, untick 'Direct' and 'Indirect' lighting influences.

![A screenshot showing the 'Direct' and 'Indirect' boxes unticked.](images/untick.png)

--- /task ---

--- task ---

Make sure that the sphere is selected (it will have an orange outline). 

Click on 'Bake'.

**Note**: This will take a few minutes. 

![An arrow points to the 'Bake' button in the 'Bake' section of the 'Render Properties' tab.](images/bake.png)

--- /task ---

--- task ---

You can now save this texture as an image, go to the drop-down with the three lines, choose 'Image' and then 'Save As'.

![A screenshot showing the menu with three lines leading to the 'Image' option with the 'Save As' option highlighted.](images/save-texture.png)

--- /task ---

--- save ---