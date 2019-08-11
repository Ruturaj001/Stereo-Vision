# Stereo-Vision

What is Stereo Vision?
  Extraction of 3D information from two or more 2D images taken from different vintage points. In simple language find distances from Camera to objects in images.

Stereo Process
  1. Extract features (points) from left and right image
  2. Match left and right image features (points) to get disparity in position
  3. Use disparity to calculate depth

This project was completed with two different techniques

Approach 1: SUM OF SQUARE DIFFERENCES
  ALGORITHM :
    • Input Left image
    • Input Right image
    • Take a pixel in left image
    • Create a window around that pixel
    • Find corresponding pixel in right image with window match
    technique
    • Choose the best pixel using SSD
    
Approach 2: BELIEF PROPAGATION (MARKOV RANDOM FIELD)
  ALGORITHM :
    • For each iteration
    • do belief propagation on right.
    • do belief propagation on left.
    • do belief propagation on up.
    • do belief propagation on down.
    • Calculate MAP (Maximum a posteriori)
  
