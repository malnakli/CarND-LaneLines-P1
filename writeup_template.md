# **Finding Lane Lines on the Road** 

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"
[region]: ./examples/regions.png 
---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of the followng steps     
1. Change the image to gray.
2. Blur the images to reduce noise with kernal 5, which it give better result
3. Detect Canny edge with 50, 250 for low and hight threshold respectfully, these the best value i found after testing it. also I need to elemenat more edges that are not stright
4. find the best region that very much fit most work images on the testing vidoes.

![alt text][region]

5. hough_lines
6. draw lines on a color image

---


In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...



### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
