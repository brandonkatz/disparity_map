# disparity_map
Small program for generating a disparity map based on 2 input images from the same scene. It is assumed that the cameras are calibrated such that epipolar scan lines in each image are parallel. Pixels in the left image are matched appropriately with those in the right by using SSD on a local block. For this computation, only the same row of pixels is evaluated since the camera is level. Objects with greater disparity in position across the 2 images will appear lighter in shade in the output, and occluded pixels appear black. Tested on images from the Middlebury dataset for stereo vision.
