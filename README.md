Vehicle Detection and Counting using YOLOv8
Overview
This repository contains a Python script that utilizes the YOLOv8 object detection model to detect and count vehicles (cars, buses, and trucks) in a video. The script processes the video frame by frame, applies a polygon mask to focus on a specific region of interest, and displays the vehicle count on the output video.
Requirements
Python 3.10+
Ultralytics library (pip install ultralytics)
OpenCV library (pip install opencv-python-headless)
PyTorch library (pip install torch)
YOLOv8 model weights (yolov8n.pt)
Usage
Clone the repository.
Download the YOLOv8 model weights (yolov8n.pt) and place it in the repository root.
Update the video_path variable in the script to point to your input video.
Run the script using python vehicle_detection.py.
The output video will be saved to the specified output_path.
Features
Vehicle detection using YOLOv8
Polygon mask to focus on a specific region of interest
Real-time vehicle counting
Output video with bounding boxes and labels
Display of total vehicle count at the end
File Structure
vehicle_detection.py: Main script
yolov8n.pt: YOLOv8 model weights
Task2.mp4: Sample input video
Task2_output.mp4: Sample output video
License
This repository is licensed under the MIT License.
Acknowledgments
Ultralytics for the YOLOv8 library and model weights
OpenCV and PyTorch libraries for their contributions to computer vision and deep learning.
