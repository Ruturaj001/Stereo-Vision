# Stereo-Vision

What is Stereo Vision?
  Extraction of 3D information from two or more 2D images taken from different vintage points. 
  In simple language find distances from Camera to objects in images.

Stereo Process
  1. Extract features (points) from left and right image
  2. Match left and right image features (points) to get disparity in position
  3. Use disparity to calculate depth

This project was completed with two different techniques

Approach 1: SUM OF SQUARE DIFFERENCES

  ALGORITHM

    1. Input Left image

    2. Input Right image

    3. Take a pixel in left image

    4. Create a window around that pixel

    5. Find corresponding pixel in right image with window match technique

    6. Choose the best pixel using SSD
    

Approach 2: BELIEF PROPAGATION (MARKOV RANDOM FIELD)

  ALGORITHM :

    1. For each iteration

    2. do belief propagation on right.

    3. do belief propagation on left.

    4. do belief propagation on up.

    5. do belief propagation on down.

    6. Calculate MAP (Maximum a posteriori)
  
