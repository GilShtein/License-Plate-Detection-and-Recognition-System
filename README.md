# License-Plate-Detection-and-Recognition-System
This project is a Python-based system for detecting and recognizing license plates in a video stream.
It utilizes object detection and tracking techniques along with optical character recognition (OCR) to identify license plate numbers from moving vehicles.
## Features
- __Vehicle Detection__: Utilizes YOLO (You Only Look Once) object detection to identify vehicles in a video stream.
- Vehicle Tracking: Employs the SORT (Simple Online and Realtime Tracking) algorithm to track vehicles across consecutive frames.
- License Plate Detection: Uses YOLO for license plate detection within the detected vehicles.
- License Plate Recognition: Applies OCR using the EasyOCR library to recognize characters on the license plates.
- License Plate Format Validation: Validates the format of recognized license plate numbers.
- Interpolation of Missing Data: Interpolates missing bounding box data for vehicles and license plates.
- Visualization: Generates a video output with annotated bounding boxes and recognized license plate numbers.
