# SFND 2D Feature Tracking

<img src="images/keypoints.png" width="820" height="248" />

I will build the feature tracking and test various detector / descriptor combinations to see which ones perform best.

* First, I will focus on loading images, setting up data structures and putting everything into a ring buffer to optimize memory load. 
* Then, I will integrate several keypoint detectors such as HARRIS, FAST, BRISK and SIFT and compare them with regard to number of keypoints and speed. 
* In the next part, you will then focus on descriptor extraction and matching using brute force and also the FLANN approach.
* In the last part, once the code framework is complete, I will test the various algorithms in different combinations and compare them with regard to some performance measures.
