# Prathiksha-ip-lab
1.Develop a program to perform linear transformation on the image.

Description: Here in the codes, we have used the getRotationMatrix function to define the parameter required in the warpAffine function to tell the function to make a matrix that can give a required rotation angle.

The warpAffine() function applies an affine transformation to the image. After applying affine transformation, all the parallel lines in the original image will remain parallel in the output image as well.

Code:

import cv2

image = cv2.imread('girl.jpg')

height, width = image.shape[:2]

center = (width/2, height/2)

rotate_matrix = cv2.getRotationMatrix2D(center=center, angle=60, scale=1)

rotated_image = cv2.warpAffine(src=image, M=rotate_matrix, dsize=(width, height))

cv2.imshow('Original image', image)

cv2.imshow('Rotated image', rotated_image)

cv2.waitKey(0)

![image](https://user-images.githubusercontent.com/95853230/148335930-87d13d63-2c2e-410b-8ebd-13de3cfd859e.png)

![image](https://user-images.githubusercontent.com/95853230/148335957-3afeb6cf-6f40-4826-85e7-699b89542322.png)
