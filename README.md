# Vanishing point detection using Canny edge detector, Hough transform, and RANSAC

## About the project
This work is to implement a vanishing point detector which returns x,y image coordinates of the point from an input image. It involves some image processing algorithms; Canny edge detection, bilateral filter, Hough transform, and RANSAC. The used photographs are one-point perspective. They have a single vanishing point within the image plane.
<br>

## Background
In Computer Vision fields, identifying edges and lines on images are fundamental to solve advanced problems such as semantic segmentation and object detection. Road Lane line detection is one of the representative examples in line detection. 
<br>

## Applied algorithms in order
**The Canny edge detector** is an edge detection operator that uses a multi-stage algorithm to detect a wide range of edges in images [1] 

**The bilateral filter** is a non-linear, edge-preserving, and noise-reducing smoothing filter for images. This preserves sharp edges [2]

**The Hough transform** finds imperfect instances of objects within a certain class of shapes by a voting procedure [3]

**Random sample consensus (RANSAC)** is an iterative method to estimate parameters of a mathematical model from a set of observed data that contains outliers, when outliers are to be accorded no influence on the values of the estimates [4]


The model performance is evaulated by a value of Mean Squared Euclidean Distance (MSED). 
<br>

## Version

OpenCV 4.5.2

## References
[1] https://en.wikipedia.org/wiki/Canny_edge_detector

[2] https://en.wikipedia.org/wiki/Bilateral_filter

[3] https://en.wikipedia.org/wiki/Hough_transform

[4] https://en.wikipedia.org/wiki/Random_sample_consensus
