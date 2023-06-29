# disparity_map
Small program for generating a disparity map based on 2 input images from the same scene. It is assumed that the cameras are calibrated such that epipolar scan lines in each image are parallel. Objects with greater disparity in position across the 2 images will appear lighter in shade in the output, and occluded pixels appear black.
