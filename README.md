# Vehical-Detection
Vehicle Detection uses YOLOv5 to identify and classify vehicles like cars, trucks, and bikes in images. Built on Google Colab, it supports real-time detection with APIs for data handling. Ideal for traffic monitoring, safety systems, and parking management, it provides accurate results with bounding boxes and classifications.

This project aims to detect and identify different types of vehicles in images using the YOLOv5 object detection model. Built on Google Colab, it leverages APIs for data processing and integration.

# Features
Vehicle Detection: Identifies vehicles in images.

Type Classification: Classifies detected vehicles (e.g., car, truck, motorcycle).

Real-Time Processing: Processes images quickly with high accuracy.

API Integration: Uses APIs for seamless data input and output.

# Installation
!git clone https://github.com/ultralytics/yolov5.git

%cd yolov5

!pip install -r requirements.txt

# Usage
Upload your images or connect to an API for input.

Run the detection script to process images and identify vehicles.

View annotated images with bounding boxes or retrieve results via API.

from yolov5 import detect

 #Perform detection on an image
results = detect(source='path_to_image.jpg', model='yolov5s')
results.show()  # Display the annotated image

# License
This project is licensed under the MIT License.

# Link
[https://youtu.be/uXhu5guONbM?si=f5h2-0qWzRd4EewQ]
