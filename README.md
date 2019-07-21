# Monocular-Camera-Calibration

Consists of writing a program that uses OpenCV to calibrate a single camera.
The calibration images are located in this archive. These are images of a calibration pattern in
which the squares have sides of 3 cm. Your program will read these images, calibrate the
camera, and output the intrinsic parameters. That is to say:
• The camera matrix containing the 2D coordinates of the optical center and the two
focal lengths (one in horizontal pixel size, and the other in vertical pixel size)
• The five distortion parameters
