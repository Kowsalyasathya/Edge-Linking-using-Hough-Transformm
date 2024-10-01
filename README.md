# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image
![image](https://github.com/user-attachments/assets/39221ea6-c00b-41b2-a033-8bed0555dd41)

![image](https://github.com/user-attachments/assets/86b33171-f5a4-4707-bcaf-853a929a1691)

### Canny Edge detector output
![image](https://github.com/user-attachments/assets/74cf9755-2802-4db4-85e1-efeab1121a66)

### Display the result of Hough transform
![image](https://github.com/user-attachments/assets/e3dac643-6cc0-4fdb-92f5-86931e80de43)

