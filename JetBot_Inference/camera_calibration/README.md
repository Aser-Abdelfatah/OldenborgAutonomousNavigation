To overcome the camera's distortion, which causes straight lines to appear curved and parts of the image appear closer than reality, we calibrated the camera using OpenCV and a checkerboard.

**data_collection.py** <br/>
Uses the JetBot camera to collect 500 images of a checkerboard.

**good_images** <br/>
This folder contains the checkerboard images used for calibration.

**camera_calibration_script.py** <br/>
This script calibrates the camera using the checkerboard images and outputs the camera matrix and distortion coefficients as well as the reprojection error. It also saves the undistorted images in a new directory.