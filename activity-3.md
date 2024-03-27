---
layout: default
title: 3-Change Image Dimensions
nav_order: 4
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

# Activity 3: Two Ways to Change Image Dimensions

In this activity we are going to change the aspect ratio of an image without cropping it so that we don't lose any quality. The reason for showing you two ways is so you learn a couple of different useful skills in GIMP while you do it. If you have any questions, please ask!

1.  Download [this image](https://pixabay.com/illustrations/ice-cream-drawing-pencil-759591/){:target="_blank"} for the exercise
2.  Open the photo in GIMP by going to **File -> Open** in the upper menu. Find where you saved the photo and open it. If your browser automatically saved it for you, it is probably in your **Downloads** folder. It may pop up with another window asking to **Convert to RGB Working Space**. (_Note: there are certain circumstances where you may need to convert an image to a different color profile, such as when importing from a scanner or camera. But in this case, it is not necessary._) Click on **Keep**

<button onclick="toggle('gif1')">Show/Hide Animation</button>
    
<div id="gif1">
    <img src="images\act-3\2-open.gif" alt="open" style="width:720px;">
    </div>
<img src="images\act-3\3-duplicatemenu.png" alt="duplicate menu" style="float:right;width:320px;margin-bottom:5px;">

3. We are first going to make a copy of this image before we edit it so that we keep a full size copy of our original. To do this, click on **Image** in the top menu and then click on **Duplicate**. <img src="images\act-3\3-duplicate.png" alt="duplicate" style="float:right;width:240px;margin-bottom:5px;">This will create a new copy of the image. You will now see above your image that you have two tabs open in GIMP with the thumbnails of the two files. If you click on the thumbnails, a little "X" appears next to the active one and at the top of the software the filename appears. The new copy will be called **[Untitled]** until you save it with a new name. <img src="images\act-3\3-untitled.png" alt="untitled" style="float:right;width:180px;">Make sure you are working in the one you plan to resize. It's best to close the original to avoid confusion by clicking on the little "X" next to the thumbnail

  <button onclick="toggle('gif2')">Show/Hide Animation</button>
 <div id="gif2">
    <img src="images\act-3\3-duplicate.gif" alt="duplicate demo" style="width:720px;">
    </div>

<img src="images\act-3\4-canvassize.png" alt="canvas size menu" style="float:right;width:360px;margin-bottom:10px;margin-left:10px;">

4.  **Changing Canvas Size:**
    -   Click on **Image -> Canvas Size**. This will pop up a window with **Canvas Size** options. For this example, we are going to turn this graphic from a rectangle into a square, so to do that we will simply make sure that the lower number in **Height** pixels is increased to the same number as the **Width** by clicking in the box and typing. Your GIMP may have this number in "Pixels" or in "Inches", feel free to use the drop down to change it. Under **Offset**, click on **Center** so that the original image will be placed in the center of the larger canvas. Then, click **Resize**
    
    <button onclick="toggle('gif3')">Show/Hide Animation</button>
<div id="gif3">
    <img src="images\act-3\4-canvassize.gif" alt="canvas size demo" style="width:720px;">
    </div>   
    
<img src="images\act-3\4-dropper.png" alt="dropper icon" style="float:right;width:90px;">

The image will now have a bigger canvas size, but the stretched canvas will have a blank, checkered background. To match the background color, click on the **Color Picker** tool (eyedropper icon) in the left toolbar. Then, use the tool to click on the yellow background of the image. This will change the foreground color in the swatches and make that exact yellow the new selected colour (see below for a before and after)
    
<img src="images\act-3\4-selectedcolorbefore.png" alt="before color select" style="float:left;width:180px;height:100px;margin-right:10px;margin-bottom:10px;">
    <img src="images\act-3\4-selectedcolor.png" alt="after color select" style="float:left;width:180px;height:100px">
        
<button onclick="toggle('gif4')">Show/Hide Animation</button>
<div id="gif4">
    <img src="images\act-3\4-dropper.gif" alt="using dropper" style="width:720px;">
    </div>

Next we will add a layer behind the image. Click on **Layer** in the top menu and then click on **New Layer**. At the bottom of the **New Layer** options window, click on the **Fill With** dropdown menu and choose **Foreground Color**. Click on **OK**. Then go to the **Layers** menu in the bottom right and drag the new layer under the image layer
    
<button onclick="toggle('gif5')">Show/Hide Animation</button>
<div id="gif5">
    <img src="images\act-3\4-layer.gif" alt="new layer" style="width:720px;">
    </div>

You should now have a full, square image with a matching background. To save it, go to **File -> Save**. When a window pops up, click **Save**. Another window will pop up, click **OK**

5.  **Save:**
-  Whenever you see the asterisks to the left of the file name up in the top center of the software, this is an indication that you've made a change to your file and have not saved it
-  Click on **File -> Save As** in the upper left corner. We are going to save this in the GIMP .xcf format, which is the working format within GIMP that will preserve the layers. Choose where you would like to save the file, and give it a name you will remember. Click **Save**. You can export a JPG or PNG of the image using instructions from Activities #1 or #2
6.  **Placing an Image:**
- For this second method, we will start with a blank canvas. Go to **File -> New**. A window will pop up with options for starting a new, blank document. Here you can choose the dimensions necessary for your project. For this one, we are going to create a letter size image. Click on the **Template** dropdown and choose **US Letter (300 ppi)** and then click **OK**. This will open up a blank, white canvas in the dimensions of a letter size sheet of paper
    
<button onclick="toggle('gif6')">Show/Hide Animation</button>
<div id="gif6">
    <img src="images\act-3\6-placing.gif" alt="placing on layer" style="width:720px;">
     </div>   

<img src="images\act-3\6-layers.png" alt="layers" style="float:right;width:240px;">
    
Click on **File -> Open as Layers**, find the original image you downloaded, and then click **Open**. This will place the image in the center of the canvas and create a new layer for it in the **Layers** panel on the right
    
<img src="images\act-3\6-bucket.png" alt="bucket icon" style="float:right;width:90px;margin-left:10px;">
     <img src="images\act-3\6-color.png" alt="color" style="float:right;width:120px;">
    
The color in your **Color Picker** should still be selected from the background from the earlier steps. Click on the **Background Layer** to make sure it is the selected layer. Then, click on the **Bucket Fill Tool** in the left toolbar (paint bucket icon). In the tool options beneath the toolbar in the left, make sure **FG color fill** is selected and **Fill whole selection**. Hover the **Bucket Fill Tool** over the white area of the image and then **click**. The colour you selected should fill in the whole white area
        
 <img src="images\act-3\7-result2.png" alt="after" style="float:right;width:180px;margin-left:10px;">
     <img src="images\act-3\7-result.png" alt="before" style="float:right;width:180px;">

7.  **Save:** To save, follow the steps from the previous activities to export the file as a JPG or PNG. If you want to preserve the layers for future editing, you can save it as a .xcf as well


<script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

<br><br><br><br>

[NEXT STEP: Activity 4](activity-4.html){: .btn .btn-blue }
