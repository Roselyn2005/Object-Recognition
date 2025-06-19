This project demonstrates real-time object detection using the YOLOv4 (You Only Look Once) deep learning model with OpenCV's DNN module and a webcam feed.

🔍 Features:
Utilizes the YOLOv4 model for high-speed, high-accuracy object detection.

Performs detection on a live webcam stream.

Draws bounding boxes and labels for detected objects using the COCO dataset classes.

Implements Non-Maximum Suppression (NMS) to eliminate redundant overlapping boxes.

🧰 Tech Stack:
Python

OpenCV

NumPy

YOLOv4 (Pre-trained weights and config)

COCO dataset class labels

📁 Files Used:
yolov4.weights – Pre-trained YOLOv4 model weights.

yolov4.cfg – YOLOv4 network configuration.

coco.names – List of 80 object class names from the COCO dataset.

💡 How It Works:
The webcam captures real-time video frames.

Each frame is converted into a blob and passed through the YOLOv4 network.

The model detects objects and outputs bounding box coordinates, class probabilities, and class IDs.

Results are filtered using confidence thresholding and non-maximum suppression.

Detected objects are highlighted with bounding boxes and labels in the live video feed.

▶️ How to Run:
Download the YOLOv4 weights, config, and coco.names file.

Make sure OpenCV and NumPy are installed.

Run the Python script and allow access to your webcam.

Press 'q' to quit or close the video window.

