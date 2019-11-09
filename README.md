# About

In this project, I have enhnaced the mammogram images using Laplacian filter and histogram equalization and implemented edge detection using canny edge detection and k-means. 

The original images used are:

![Mammogram1](https://github.com/Anniebbb/ImageProcessing/blob/master/mam1.jpg) ![Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/mam2.jpg)  ![Mammogram4](https://github.com/Anniebbb/ImageProcessing/blob/master/mam4.jpg)
![Mammogram3](https://github.com/Anniebbb/ImageProcessing/blob/master/mam3.jpg)


# Enhancement

I have converted the images into arrays and convolved them with a 3x3 kernel to obtain the Laplacian of the images. The Laplacian is then subtracted from the images to get the Laplacian filtered images.


![Laplacian Mammogram1](https://github.com/Anniebbb/ImageProcessing/blob/master/lap1.jpg) ![Laplacian Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/lap2.jpg) ![Laplacian Mammogram4](https://github.com/Anniebbb/ImageProcessing/blob/master/lap4.jpg)
![Laplacian Mammogram3](https://github.com/Anniebbb/ImageProcessing/blob/master/lap3.jpg)

I also applied Contrast-limited adaptive histogram equalization (CLAHE) to the images. The results were:

![Histogram Equalized Mammogram1](https://github.com/Anniebbb/ImageProcessing/blob/master/h1.jpg) ![Histogram Equalized Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/hp2.jpg) ![Histogram Equalized Mammogram4](https://github.com/Anniebbb/ImageProcessing/blob/master/h4.jpg)
![Histogram Equalized Mammogram3](https://github.com/Anniebbb/ImageProcessing/blob/master/h3.jpg)


# Edge Detection
