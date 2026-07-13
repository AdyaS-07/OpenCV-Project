# IMAGE PROCESSING USING OPENCV FUNCTIONS

A simple OpenCV project built using Python that explores fundamental image processing techniques used in computer vision.
The project demonstrates how different preprocessing methods improve image quality, reduce computational complexity and prepare images for feature extraction and object detection.

PROJECT OVERVIEW:
This project implements a complete image processing pipeline using OpenCV. 
Different image transformations, filtering techniques, thresholding methods, morphological operations and contour detection algorithms were explored to understand their applications in real-world computer vision systems. 
The project also includes video frame processing and GIF generation to demonstrate that the same preprocessing techniques can be applied to videos.

FEATURES: 
•	Image Reading and Display
•	Image Saving
•	Image Properties
•	Image Resizing
•	Cropping
•	Flipping
•	Rotation
•	RGB, Grayscale and HSV Colour Spaces
•	Channel Splitting and Merging
•	Average Blur
•	Gaussian Blur
•	Median Blur
•	Bilateral Filtering
•	Binary Thresholding
•	Adaptive Thresholding
•	Otsu Thresholding
•	Canny Edge Detection
•	Morphological Operations
•	Contour Detection
•	Bounding Boxes
•	Object Centre Detection
•	Shape Approximation
•	HSV Colour Detection
•	Bitwise Operations
•	Histogram Equalization
•	Video Processing
•	GIF Generation
•	Performance Comparison using Different Image Sizes


1.	Image Transformations:
The project demonstrates:
•	Resizing
•	Cropping
•	Rotation
•	Flipping
•	Colour Space Conversion
•	Noise Removal
•	Image Enhancement
•	Object Boundary Detection

2.	Morphologiacal Operations:
Help improve image quality before contour detection.
The following operations were implemented:
•	Erosion
•	Dilation
•	Opening
•	Closing
•	Morphological Gradient
•	Top Hat
•	Black Hat

3.	Video Processing:
The project also processes videos frame-by-frame using OpenCV.
Each frame undergoes:
•	Image Resizing
•	Grayscale Conversion
•	Gaussian Blur
•	Edge Detection
The processed frames are combined to generate a processed GIF.


RESULTS:
The project demonstrates:
•	Image preprocessing techniques
•	Noise reduction
•	Edge detection
•	Colour segmentation
•	Shape and contour detection
•	Histogram enhancement
•	Video frame processing
•	GIF visualization
•	Computational optimization using image resizing

FUNCTIONS USED:
•	cv2.imread()
•	cv2.imwrite()
•	cv2.resize()
•	cv2.cvtColor()
•	cv2.flip()
•	cv2.getRotationMatrix2D()
•	cv2.warpAffine()
•	cv2.split()
•	cv2.merge()
•	cv2.blur()
•	cv2.GaussianBlur()
•	cv2.medianBlur()
•	cv2.bilateralFilter()
•	cv2.threshold()
•	cv2.adaptiveThreshold()
•	cv2.Canny()
•	cv2.erode()
•	cv2.dilate()
•	cv2.morphologyEx()
•	cv2.findContours()
•	cv2.drawContours()
•	cv2.contourArea()
•	cv2.arcLength()
•	cv2.boundingRect()
•	cv2.moments()
•	cv2.approxPolyDP()
•	cv2.inRange()
•	cv2.bitwise_and()
•	cv2.equalizeHist()
•	cv2.VideoCapture()
•	cv2.VideoWriter()

Sample photo used: <img width="1536" height="1024" alt="beach" src="https://github.com/user-attachments/assets/d9debf9b-dbc8-439b-9bf0-c2b9e58a3504" />
Sample Video used: <img width="320" height="320" alt="dance" src="https://github.com/user-attachments/assets/39be384b-9c77-4828-80a2-119ba43cc7e4" />



AUTHOR:
Adyasha Sahani
