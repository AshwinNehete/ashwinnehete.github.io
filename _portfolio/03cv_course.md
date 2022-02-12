---
title: "Computer Vision"
excerpt: ""
collection: portfolio
youtubeId: N9ytb3cLnX4
youtubeId1: JWJpqS6nR90
youtubeId2: AplkxzoV1uQ
---

`16720 Coursework - Fall 2020`

## Spatial Pyramid Matching for Scene Classification
* Built a representation based on bags of visual words and used spatial pyramid matching for scene classification.
<br/><img src='/images/cv_hw1_categories.png'>

* The program is able to classify images into 8 types of scenes. The following figure illustrates the overview of the bag-of-words approach implemented in this task :
<br/><img src='/images/cv_hw1_overview.png'>

## Augmented Reality with Planar Homographies
* Implemented an AR application by using planar homographies.
    * The program finds the correspondences between two images using BRIEF Descriptor.
    * Estimates the homography between the images.
    * The images are then warped to overlay a Harry Potter image onto a Computer Vision textbook cover.
    * This is further extended to videos to generate an Augmented Reality application depicted in the following video.

{% include youtubePlayer.html id=page.youtubeId %}

## Lucas-Kanade Tracking
* Implemented a simple Lucas-Kanade (LK) tracker with one single template.
    * This tracker uses a pure translation warp to track a particular template throughout the video.
    * I also account for the template drifting issue by updating the template as the video progresses.
{% include youtubePlayer.html id=page.youtubeId1 %}
{% include youtubePlayer.html id=page.youtubeId2 %}

* Implemented a motion subtraction method for tracking moving pixels in a scene.
* Studied efficient tracking using inverse composition.

## 3D Reconstruction
* Created a 3D Reconstruction of an object given a stereo-pair images of the object.
    * Estimated the Fundamental Matrix using eight-point and seven-point algorithms.
    * Calculated the Essential Matrix using the Fundamental Matrix and calibrated camera intrinsics.
    * Used triangulation method to obtain a 3D metric reconstruction from 2D correspondences.

## Neural Networks for Recognition
* Implemented a fully connected Neural network that can recognize handwritten letters in an image using the NIST36 dataset to a test accuracy of around 76%.

## Photometric  Stereo
* Rendering the n-dot-i lighting
* Calibrated Photometric Stereo - Lighting directions are given
* Uncalibrated Photometric Stereo - No lighting directions are given

<!-- > Quote

<br/><img src='/images/500x300.png'> -->