# 20-20-replacement

# Specification of Function

Basically Users should be able to upload 2 images to a folder (or even better yet the program asks them to select 2 images), the program then displays the both images and asks for the user to click them. On click (x,y) are registered. The distance between the 2 points is found. 

Things to be aware of:
* size of the photos should be the same, (how to get image proportions?)
* name of photos affects their import (unless you can find a way to circumvent it)
* output is (delta_x, delta_y)
* you're displaying 2 images at the same time. So when you load the application and are displaying the images, you have to be aware of the spacing between them and how that spacing could change, depending on the image size. This affects your mouse click calculations, (i.e. when calculating point(x,y) = click(x,y) - spacing(x,y), the amount of your spacing varies)
