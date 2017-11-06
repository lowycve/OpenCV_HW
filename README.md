# OpenCV_HW
## Exercise 1:

we can access the pixel value of cvMat by 1)using the pointer, 2)the indexing operator, 3)using Matlterator object, 4)using the .at(x,y) where x, y is the row and col of matrix. 

For the RGB picture, there are 3 color channels called B,G,R and we need to multiply the number of column and the number of rows to scan the matrix.

## Exercise 2:

1.After running the ColorImage.cpp, we got 10 different output images which are RED, GREEN, BLUE, Cr, Cb, Y, Value, Hue and Saturation and original. For the Red, Green and Blue, they are the three channels of the original image, after being splited, they are displayed seperately and each of them has a seperate value. If a certain part of the original image are blue, then the value of the blue channel are bigger than other 2 channels there. For the YCRCB part, Y stands for the luminance, and CB and CR are the blue and red color differences, if the CB image we got is dark, then it shows that the blue component of the CB image is greater than others, while the Cr shows the proportion of the red component, if the CR image is dark then the original image will tend to be red. For HSV images, Hue image says how dark is the original image, Value shows how bright the original image is and Saturation shows the shadows of the original image.

2.The value of the RGB, YCRCB and HSV shows in the picture below.

<img width="391" alt="screen shot 2017-11-05 at 8 54 11 pm" src="https://user-images.githubusercontent.com/31743714/32423136-ab93157e-c272-11e7-9e31-5cd1664b360b.png">

the range of pixel values for each colorspaces are all [0,255]

## Exercise 3:

Please find in the exercise3 folder

## Exercise 4:

1.when we set the threshold value higher, we got a brighter picture which means that the thresholded picture tend to be white. Also, the band threshold picture tend to be brighter. But the Binary threshold value tend to be darker.

2.The binary threshold requires a specific light environment to be applied and you can not extend the application to 3D, also, binary threshold will lose a huge amount of information in the picture.

3.When the environment changes rapidly, the adaptive threshold will be useful, like the varing illumination, or the background changes a lot.
