# ChromaCanvas
Real-Time Color Detection and Tracking using OpenCV
This project demonstrates a real-time color detection and tracking system using OpenCV. The application allows you to dynamically select colors for tracking, adjust the color range through HSV trackbars for accurate detection, and clear the canvas via on-screen buttons.

Features
Real-time Color Detection: Detect and track colored markers or objects in real time.
Dynamic Color Selection: On-screen buttons allow you to change the color to be tracked dynamically.
Canvas Clearing: A button to clear the drawing canvas.
Customizable Color Ranges: Use HSV trackbars to fine-tune the color detection range for more accurate tracking.
Requirements
Before running the project, ensure you have the following installed:

Python 3.x
OpenCV library
You can install OpenCV via pip:

bash
Copy code
pip install opencv-python
How to Run
Clone the repository or download the project files.
Run the Python script:
bash
Copy code
python color_detection.py
A window will open with the webcam feed.
Use the HSV trackbars to adjust the color range for the object you want to detect.
Click the on-screen buttons to change the color or clear the canvas.
Customization
Color Ranges: The HSV trackbars allow you to adjust the Hue, Saturation, and Value for precise color detection.
On-Screen Buttons: Use these buttons to:
Change the color of the marker for drawing on the canvas.
Clear the canvas.
Libraries Used
OpenCV: For capturing webcam input, detecting colors, and tracking objects.
NumPy: For handling pixel data.
How It Works
Webcam Feed: The application captures the real-time video feed from your webcam.
Color Detection: The object’s color is detected by converting the frame from BGR to HSV color space and applying the color mask.
Tracking: The detected object is tracked and drawn on a canvas, with options to change the drawing color or clear the canvas entirely.
Screenshots
(Include screenshots of the application running here)

License
This project is licensed under the MIT License.


