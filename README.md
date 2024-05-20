# CANNY EDGE DETECTION
## Aim:
To perform edge detection using Canny edge detector.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
Step1:
Import all the necessary modules for the program.

Step2:
Load a image using imread() from cv2 module.

Step3:
Convert the image to grayscale

Step4:
Using Sobel operator from cv2,detect the edges of the image.

Step5:
 Using Canny operator from cv2,detect the edges of the image.

## Program:
```
DEVELOPED BY:JANANI.S
REG NO:212222230049
```
```PYTHON
import cv2
import numpy as np
import matplotlib.pyplot as plt
img=cv2.imread("peacock.jpg")
cv2.imshow("original image",img)
cv2.waitKey(0)
cv2.destroyAllWindows()

canny=cv2.Canny(gray,120,150)
cv2.imshow("canny edge detection",canny)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
## Output:

![cedoi](https://github.com/JananiSoundararajan/CANNY-EDGE-DETECTION/assets/119477549/01d2729c-48ea-4125-a646-00695dd75b58)

![canny](https://github.com/JananiSoundararajan/CANNY-EDGE-DETECTION/assets/119477549/47711807-192a-4ed6-9115-88141bc64a2a)

## RESULT:
   Hence edge detection is done successfully using Canny edge detector.
