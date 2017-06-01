# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:

* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[challenge]: ./writeup_resources/challenge.png
[solidWhiteRight]: ./writeup_resources/solidWhiteRight.png
[solidYellowLeft]: ./writeup_resources/solidYellowLeft.png

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.



### 2. Identify potential shortcomings with your current pipeline


	It looks nice catching white and yellow lane but it's only a good condition.

	1. There are no other cars in the near front sight
	2. The time zone is daylight
	3. There are no obstacles on the floor like a snowy, rainy .. 
	4. There is no shadow


![alt text][solidWhiteRight]

![alt text][solidYellowLeft]

	It could not distinguish the shadow and the vehicle.

![alt text][challenge]



### 3. Suggest possible improvements to your pipeline

	1. Increase the contrast of photographs
	2. Predict the next lane
