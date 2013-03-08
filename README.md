# EdgeDetector

This code implements OpenCV based Canny Edge Detector. Sample input image is included along with this project. There is a file called "CMakeLists.txt". This file will used to build the project (if you have built OpenCV using cmake). If not, just use the .cpp file in your project and build it. To build using command line, follow the steps below to get it up and running:

	$ cmake .
	$ make
	$ ./main inputImage.jpg

The output will be displayed on a window along with a trackbar. Move the trackbar to adjust the threshold and get different levels of sensitivity for edge detection.