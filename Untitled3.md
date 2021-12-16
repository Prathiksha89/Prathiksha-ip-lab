```python
# Python program to explain cv2.imshow() method

# importing cv2
import cv2

# path



# Reading an image in default mode
image = cv2.imread('cat.jpg')

# Window name in which image is displayed
window_name = 'Image'

# Using cv2.imshow() method
# Displaying the image
image=cv2.cvtColor(image,cv2.COLOR_BGR2HSV)
cv2.imshow(window_name, image)

#waits for user to press any key
#(this is necessary to avoid Python kernel form crashing)
cv2.waitKey()

#closing all open windows
cv2.destroyAllWindows()
image= cv2.imread('cat.jpg')
res = cv2.resize(img,None,fx=2, fy=2, interpolation = cv.INTER_CUBIC)
```


```python

```


```python

```
