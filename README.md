# About

In this project, I have enhnaced mammogram images using Laplacian filter and histogram equalization. After this, I have implemented edge detection using canny edge detection and k-means clustering for segmentation. 

The original images used are:

![Mammogram1](https://github.com/Anniebbb/ImageProcessing/blob/master/mam1.jpg) ![Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/mam2.jpg)  ![Mammogram4](https://github.com/Anniebbb/ImageProcessing/blob/master/mam4.jpg)
![Mammogram3](https://github.com/Anniebbb/ImageProcessing/blob/master/mam3.jpg)


# Enhancement

I have converted the images into arrays and convolved them with a 3x3 kernel to obtain the Laplacian of the images. The Laplacian is then subtracted from the images to get the Laplacian filtered images.


![Laplacian Mammogram1](https://github.com/Anniebbb/ImageProcessing/blob/master/lap1.jpg) ![Laplacian Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/lap2.jpg) ![Laplacian Mammogram4](https://github.com/Anniebbb/ImageProcessing/blob/master/lap4.jpg)
![Laplacian Mammogram3](https://github.com/Anniebbb/ImageProcessing/blob/master/lap3.jpg)

I also applied Contrast-limited adaptive histogram equalization (CLAHE) to the images. The results were:

![Histogram Equalized Mammogram1](https://github.com/Anniebbb/ImageProcessing/blob/master/h1.jpg) ![Histogram Equalized Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/h2.jpg) ![Histogram Equalized Mammogram4](https://github.com/Anniebbb/ImageProcessing/blob/master/h4.jpg)
![Histogram Equalized Mammogram3](https://github.com/Anniebbb/ImageProcessing/blob/master/h3.jpg)


# Edge Detection

K - means clustering algorithm is an unsupervised algorithm and it is used to segment the interest area from the background. 
Canny operator is widely used as an excellent edge detector; it also includes Gaussian smoothing element that may significantly soften edges. I have added k-means segmentation and have compared edge detection prior and post k-means segmentation. I have applied median filtering to the image prior to edge detection, to get rid of speckle noise. The enhanced image is from the histrogram equalization.

Given below is the entire process for mammogram number 2.

![Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/m1.jpg) ![Enhanced Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/m2.jpg) ![Manual Parameters Edge Detection Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/m3.jpg) ![ Automnated Edge Detection Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/m4.jpg) ![K means segmented with k=3 Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/m5.jpg) ![Manual Parameters Edge Detection on K means segmented Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/m6.jpg) ![Automated Edge Detection on K means segmented Mammogram2](https://github.com/Anniebbb/ImageProcessing/blob/master/m7.jpg)

# Conclusion
It is clearly seen that the edge detection is better after the image has been segmented by using the k-means clustering. And also, the manual edge detection is better than the automatic one in both cases - before and after segmentation using k-means. 
