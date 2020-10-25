# Lane-Detection
Built a project that detects lanes in video/picture which is a key component for self driving cars.
<div align=”center”src=" ![ezgif com-gif-maker](https://user-images.githubusercontent.com/52134872/97106629-f2ffb480-16e8-11eb-9f4f-9adf1082f9b9.gif)"> </div>
## How it works
We can describe this process in a straightforward way. 

- Detect the lane lines by looking at color contrast gradients in the image
- fit a curve to the points that make the line
- draw the red lines on top of the lane lines

This is an algorithm that uses Canny Edge detection hough transformations and polynomial regression to determine the the edges of lines in order to perform lane detection



## Steps-
1. First, it converts the image into grey scale and then using **Canny edge detection** detects all the edges in the image.
2. Then only to extract the lanes and remove the background scene take the bitwise or with a white triangle on a black background.
3. Then using **Houghs Transformation** and weighted slope of edeges fine tune the detected edges.  


Built this project in **python** language with the help of **OpenCv** library.
### Requirements 
- numpy
- python3
- opencv

