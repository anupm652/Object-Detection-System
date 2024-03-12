# Object Detection System

This project is designed for object detection using the Single Shot MultiBox Detector (SSD) model with MobileNetV3 architecture. It allows users to detect objects in images, videos and real time camera.

## Files

- `Image.ipynb`: Jupyter Notebook for object detection on static images.
- `Video.ipynb`: Jupyter Notebook for object detection on video streams.
- `Video.mp4`: Sample video file for testing the system.
- `download1.jpg`: Sample image for testing object detection.
- `frozen_inference_graph.pb`: Pre-trained SSD model (frozen inference graph).
- `labels.txt`: List of object class labels.
- `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt`: Model configuration file.

## Usage

1. **Install the required dependencies**:
   - Ensure you have Python 3.x installed on your system.
   - Install the necessary packages using pip:
     ```bash
     pip install opencv-python pandas numpy imutils
     ```

2. **Clone the repository**:
   - Clone this repository to your local machine.

3. **Run the file for image color detection**:
   - Run the following file for image color detection:
     ```
     Image.ipynb
     ```

4. **Run the file for live video color detection**:
   - Run the file for live video color detection using Python:
     ```
     Video.ipynb
     ```

5. **Interact with the application**:
   - Click on a color within the displayed image or video frame.
   - The application will display the color name and RGB values of the clicked color.

## Contributing

Contributions are welcome! If you have a feature request, bug report, or want to improve the code, please open an issue or submit a pull request.
