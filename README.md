# OpenCV_HW
# Exercise 1:

we can access the pixel value of cvMat by 1)using the pointer, 2)the indexing operator, 3)using Matlterator object, 4)using the .at(x,y) where x, y is the row and col of matrix. 

For the RGB picture, there are 3 color channels called B,G,R and we need to multiply the number of column and the number of rows to scan the matrix.

# Exercise 2:

1.After running the ColorImage.cpp, we got 10 different output images which are RED, GREEN, BLUE, Cr, Cb, Y, Value, Hue and Saturation and original. For the Red, Green and Blue, they are the three channels of the original image, after being splited, they are displayed seperately and each of them has a seperate value. If a certain part of the original image are blue, then the value of the blue channel are bigger than other 2 channels there. For the YCRCB part, Y stands for the luminance, and CB and CR are the blue and red color differences, if the CB image we got is dark, then it shows that the blue component of the CB image is greater than others, while the Cr shows the proportion of the red component, if the CR image is dark then the original image will tend to be red. For HSV images, Hue image says how dark is the original image, Value shows how bright the original image is and Saturation shows the shadows of the original image.

2.The value of the RGB, YCRCB and HSV shows in the picture below.
