## Create an image of your texture

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Create a reusable image of your **texture**.
</div>
<div>
![The output of this step.](images/baked-image.png){:width="300px"}
</div>
</div>

### Create a blank image

--- task ---

Go to the **Image Editor** in the bottom left-hand corner of the Shading workspace. Open the drop-down menu (with the icon with three lines) and click on **Image**, then **New**:

![The Image Editor drop-down menu open, with 'Image' then 'New' highlighted.](images/image-viewer.png)

Give your image a sensible name like `MyTexture` and click on **OK** to create the black/empty image: 

![The New Image pop-up window with "MyTexture" in the Name field.](images/new-image.png)

--- /task ---

--- task ---

**Add** a new **Image Texture**. Go to **Add** > **Texture** > **Image Texture**:

![The Add menu open in the material window, with 'Texture' then 'Image Texture' highlighted.](images/image-texture.png)

--- /task ---

--- task ---

Place the **Image Texture** box away from your other boxes:

![The Image Texture box positioned away from the other boxes in the material window.](images/place-texture.png)

--- /task ---

--- task ---

Go to your new **Image Texture** box. Click on the **Browse Image** icon.

Select the image that you just created. You may have named this `MyTexture`:

![The Browse Image icon highlighted in the Image Texture box, and a menu open with 'MyTexture' selected.](images/add-mytexture.png)

--- /task ---

### Use Bake to map your material onto the image

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Texture baking**</span> is the process of taking complex surface data from a 3D object and saving it to a 2D image. The image can then be used on another 3D object or even exported to be used in another piece of software.

![A strip of images showing a texture on a sphere, then as a flat image, and then on a cylinder, cube, and cone.](images/texture-baking.png)
</p>

--- task ---

Go to the **Render Properties** tab on the right-hand side of the workspace.

To use **Bake**, change the **Render Engine** to **Cycles**:

![The Render Properties tab open in Blender. The Render Properties icon is highlighted. It is a grey camera. In the Render Properties tab, the Render Engine drop-down menu is open, with 'Cycles' highlighted.](images/render-engine.png)

--- /task ---

--- task ---

The most common type of texture baking is **Diffuse baking**.

In the **Render Properties** tab, expand the **Bake** panel and change the **Bake Type** to **Diffuse**:

![The Bake panel open in the Render Properties tab. In the Bake panel, the Bake Type drop-down menu is open, with 'Diffuse' highlighted.](images/diffuse-bake.png)

--- /task ---

--- task ---

In the **Bake** panel, untick **Direct** and **Indirect** lighting influences:

![The 'Direct' and 'Indirect' boxes unticked in the Bake panel.](images/untick.png)

--- /task ---

--- task ---

Make sure that the sphere is selected (it will have an orange outline). 

Click on **Bake**:

![The 'Bake' button highlighted in the Bake panel.](images/bake.png)

**Note:** It will take a few minutes for your image to be created: 

![The Image Editor with a square image showing the patterns and colours from the sphere arranged in a 2D image.](images/baked-image.png)

--- /task ---

### Save your image

--- task ---

You can now save this texture as an image. Go to the drop-down menu in the Image Editor (the icon with three lines) and choose **Image**, then **Save As...**:

![The Image Editor drop-down menu open, with 'Image' then 'Save As...' highlighted.](images/save-texture.png)

--- /task ---

--- save ---