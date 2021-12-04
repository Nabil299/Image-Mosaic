# Image-Mosaic
Creating Panormaic View by getting key points between images then compute homography matrix and stitch the images to each other 
<h1> First </h1>
<p> we click on correspondence points in both images, and define them as our key points </p>
<h1> Second </h1>
<p> we compute Homography matrix which is 3x3 matrix according to the key points from both images </p>
<h1> Third </h1>
<p> Forward Warping for new positions, followed by inverse Warping to fill up intensity values using Bilinear Interpolation</p>
<h1> Finally</h1>
<p> Create a new image that can hold both images and stitch them together</p>
