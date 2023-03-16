# READ AND WRITE AN IMAGE
## AIM
To write a python program using OpenCV to do the following image manipulations.
i) Read, display, and write an image.
ii) Access the rows and columns in an image.
iii) Cut and paste a small portion of the image.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Choose an image and save it as a filename.jpg
### Step2:
Use imread(filename, flags) to read the file.
### Step3:
Use imshow(window_name, image) to display the image.
### Step4:
Use imwrite(filename, image) to write the image.
### Step5:
End the program and close the output image windows.
## Program:
### Developed By:
### Register Number: 
i) #To Read,display the image
```python
### Developed By: DHARANESH
### Register Number: 212222240062
import cv2
spd_mn=cv2.imread('flower.jpeg',1)
cv2.imshow('DHARANESH(22000785)',spd_mn)
cv2.waitKey(0)

```
ii) #To write the image
```python
### Developed By: DHARANESH
### Register Number: 212222240062
import cv2
A=cv2.imread("flower.jpeg",1)
cv2.imwrite("flower.jpeg",A)
cv2.imshow("(Dharanesh)212222240062",A)
cv2.waitKey(0)



```
iii) #Find the shape of the Image
```python
### Developed By: DHARANESH
### Register Number: 212222240062

import cv2 
colorImage = cv2.imread('flower.jpeg',1)
print(colorImage.shape)






```
iv) #To access rows and columns

```python
### Developed By: DHARANESH
### Register Number: 212222240062
import random
import cv2
A=cv2.imread("flower.jpeg",1)
for i in range(100):
    for j in range(A.shape[1]):
        A[i][j]=[random.randint(0,255),random.randint(0,255),random.randint(0,255)]
cv2.imshow("Dharanesh(212222240062)",A)
cv2.waitKey(0)




```
v) #To cut and paste portion of image
```python
### Developed By: DHARANESH
### Register Number: 212222240062
#To cut and paste portion of image
import cv2
color_img = cv2.imread('flower.jpeg',1)
tag = color_img[20:80,20:80]
color_img[90:150,90:150] = tag
cv2.imshow('Dharanesh-2222240062',color_img)
cv2.waitKey(0)



```

## Output:

### i) Read and display the image

![1](https://user-images.githubusercontent.com/118707669/225695242-2a7af923-9c93-4c8d-a9e6-78dabfc3ec2f.jpg)


### ii)Write the image

![2](https://user-images.githubusercontent.com/118707669/225695445-39693b66-f6e0-43c2-9ad5-e6a723d4bac9.jpg)


### iii)Shape of the Image

![size 3](https://user-images.githubusercontent.com/118707669/225695498-01fb84b4-43b5-42e9-a1c5-d158b329339c.jpg)


### iv)Access rows and columns
![4](https://user-images.githubusercontent.com/118707669/225695561-cc220b12-2367-4a7f-abd9-068a612d48de.jpg)


### v)Cut and paste portion of image
![cut 5](https://user-images.githubusercontent.com/118707669/225695654-c901cd98-b0d4-4713-8603-7f0a3352b599.jpg)


## Result:
Thus the images are read, displayed, and written successfully using the python program.


