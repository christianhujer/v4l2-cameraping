# v4l2-cameraping

![C CI](https://github.com/christianhujer/v4l2-cameraping/workflows/C%20CI/badge.svg)

Camera ping command for video4linux2.

It activates a camera, reads from stdin and deactivates the camera.
The purpose is for multi-device position calibration:
If you have 3 webcams attached, how do you know which device is which webcam?
This tool helps by activating a webcam.
So, in a script you could activate the webcams one after another in order to find out which device is which webcam.
