# Lane-Detection
Built a project that detects lanes in video/picture which is a key component for self driving cars.
![image](https://user-images.githubusercontent.com/52134872/97107095-b41f2e00-16eb-11eb-947e-cd83d6cb8d61.png)

Steps-
1. First, it converts the image into grey scale and then using Canny edge detection detects all the edges in the image.
2. Then only to extract the lanes and remove the background scene take the or bit a triangular image.
3. Then using Houghs Transformation and weighted slope of edeges fine tune the detected edges.  

![ezgif com-gif-maker](https://user-images.githubusercontent.com/52134872/97106629-f2ffb480-16e8-11eb-9f4f-9adf1082f9b9.gif)

Made this project in python language with the help of OpenCv library.
