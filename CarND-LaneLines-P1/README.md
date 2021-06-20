# **Finding Lane Lines on the Road** 


The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image0]: <img width="400" height="400" src="./test_images_output/solidWhiteCurve_step0_orig.jpg">
[image1]: ./test_images_output/solidWhiteCurve_step1_gray.jpg "Grayscale"
[image2]: ./test_images_output/solidWhiteCurve_step2_cann.jpg "Canny"
[image3]: ./test_images_output/solidWhiteCurve_step3_intrst.jpg "ROI"
[image4]: ./test_images_output/solidWhiteCurve_step4_hough.jpg "Hough"
[image5]: ./test_images_output/solidWhiteCurve_step5_weight.jpg "Overlapped"

---

### Reflection

### 1. Pipeline 


My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I .... 

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...

If you'd like to include images to show how the pipeline works, here is how to include an image: 

![alt text][image0]
<img src="./test_images_output/solidWhiteCurve_step0_orig.jpg" width="300">
![alt text][image1]
![alt text][image2]
![alt text][image3]
![alt text][image4]
![alt text][image5]

### 2. draw_lines() function

### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
