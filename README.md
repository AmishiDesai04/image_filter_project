**Image Filter Project – Python**

Overview
The Image Filter Project is a Python-based application designed to enable users to apply a variety of image filters to their images. This versatile tool allows users to select an image from their device, capture an image using their webcam, or utilize a default image. The application offers several filter options, including grayscale, inverted, blur, sketch, watercolor, and pencil sketch.

Features
•	Image Selection: Users can choose to:
•	Select from Device: Browse and open an image file from their computer.
•	Capture Image: Use the webcam to capture a new image.
•	Default Image: Use a pre-defined default image.

Filter Options: Users can apply the following filters to their selected image:
•	Grayscale: Convert the image to grayscale.
•	Inverted: Invert the colors of the image.
•	Blur: Apply a blur effect to the image.
•	Sketch: Convert the image to a pencil sketch.
•	Watercolor: Apply a watercolor effect to the image.
•	Pencil Sketch: Create a detailed pencil sketch of the image.
Prerequisites
To run this project, ensure that you have the following software installed:
•	Python 3.x
•	Pillow: pip install pillow
•	OpenCV: pip install opencv-python
•	NumPy: pip install numpy
•	Tkinter: Typically included with Python installations
Installation
1.	Clone the Repository:
sh
Copy code
git clone https://github.com/yourusername/image-filter-project.git cd image-filter-project 
2.	Install Required Libraries:
sh
Copy code
pip install pillow opencv-python numpy 
Usage
1.	Run the Application:
sh
Copy code
python image_filter.py
1.	Select an Image:
•	From Device: Choose the "Select from your device" option and browse to select an image file.
•	Capture Image: Choose the "Capture Image" option to use the webcam. Follow the on-screen instructions to capture an image.
•	Default Image: Choose the "Default Picture" option to use the predefined image.
2.	Apply Filters: Use the provided buttons to apply different filters to the selected image:
•	Inverted
•	Gray Scale
•	Blur
•	Sketch
•	Water Color
•	Pencil Sketch
3.	Exit: Click the "Exit" button to close the application.
Project Structure
•	image_filter.py: Main Python script that runs the application.
•	default.jpg: Default image used when the "Default Picture" option is selected.
