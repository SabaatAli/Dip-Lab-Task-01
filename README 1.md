\\ DIP Task 01 – Introduction to Digital Image Processing

Overview
This project introduces the basic operations of digital image processing using Python. The program reads a color image, verifies successful loading, performs color space conversion, extracts color components, and generates grayscale and binary representations for visualization and analysis.

Objectives
To read a color image from a file path
To verify successful image loading
To convert the image from BGR to RGB format
To extract and visualize individual color channels
To convert the image into grayscale
To generate a binary image using thresholding
To display all results using Matplotlib subplots

Tools & Libraries Used
Python
OpenCV (cv2)
NumPy
Matplotlib

Processing Steps
1. Image Loading
The program reads a color image from a specified file path and checks whether the image is loaded successfully.

2. Color Space Conversion
Since OpenCV loads images in BGR format, the image is converted to RGB for correct display using Matplotlib.

3. RGB Channel Extraction
The Red, Green, and Blue color components are extracted and displayed separately to analyze their individual intensity distributions.

4. Grayscale Conversion
The RGB image is converted into a grayscale image, reducing color information while preserving intensity details.

5. Binary Image Generation
Thresholding is applied to the grayscale image to create a binary image that separates foreground from background.

Results Visualization
Using Matplotlib subplots, the program displays:
Original RGB image
Red, Green, and Blue color component images
Grayscale image
Binary thresholded image
All outputs are presented in a single, organized figure for easy comparison.

Applications
Learning basic image processing concepts
Image preprocessing for computer vision
Educational digital image processing experiments

Conclusion
This task provides a foundation for understanding digital image processing workflows. By performing basic transformations and visualizations, it prepares the groundwork for more advanced image analysis tasks.