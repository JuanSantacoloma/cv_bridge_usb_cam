# Process to replicate results
## usb_cam
This package is used for get access to the image from cams that works with USB like laptops cams.
In a new terminal we use:

`roslaunch usb_cam usb_cam-test.launch`

With this command we have the image publish in some topics, depending on the cam you will have more information.
The specific topic we use is:

`/usb_cam/image_raw/compressed`

## cv_bridge

The ROS package for openCV, in the scripts folder you can fing the python code for ORB (fusion of FAST keypoint detector and BRIEF descriptor) and node creation inside ROS, the command is:

`roslaunch cv_camera_orb cv_bridge_test.launch`

