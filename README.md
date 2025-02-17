# Image Grayscale Conversion and Edge Detection
This project implements a Python script that converts a color image to grayscale and detects its edges using various image processing techniques. The program is built using popular libraries such as OpenCV and NumPy to perform the core image manipulation tasks.

# Features
Color to Grayscale Conversion: Converts a color image to a grayscale image using OpenCV functions.
Edge Detection: Detects the edges in the image using the Canny edge detection algorithm.
Save Results: Saves the processed grayscale image and the edge-detected image as separate files.
# Requirements
Python 3.x

OpenCV (opencv-python)

NumPy (numpy)


You can install the required libraries by running:

bash
Copy
pip install opencv-python numpy
Usage
Clone this repository to your local machine:

bash
Copy
git clone https://github.com/yourusername/image-grayscale-edge-detection.git
Navigate to the project directory:

bash
Copy
cd image-grayscale-edge-detection
Place the image you want to process in the project directory or specify its path.

Run the script to convert the image to grayscale and detect edges:

bash
Copy
python convert_and_detect.py --input your_image.jpg
Replace your_image.jpg with the actual file name of the image you want to process.
The output will be saved as:

grayscale_image.jpg: The grayscale version of the input image.
edge_detected_image.jpg: The edge-detected version of the input image.
Example
Here is an example of how the input and output might look:

Input:
A colorful image of a city skyline.
Output:
A grayscale version of the image.
An edge-detected version highlighting the edges of the buildings and structures.
Script Explanation
Grayscale Conversion: Uses OpenCV's cv2.cvtColor() function to convert the input image to grayscale.

Edge Detection: The edge detection is achieved through the Canny edge detection algorithm implemented in OpenCV using cv2.Canny().

Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions, bug reports, and feature requests are always welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.

Let me know if you'd like to add any other sections!
