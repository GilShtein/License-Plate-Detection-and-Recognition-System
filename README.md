# License-Plate-Detection-and-Recognition-System
This project is a Python-based system for detecting and recognizing license plates in a video stream.
It utilizes object detection and tracking techniques along with optical character recognition (OCR) to identify license plate numbers from moving vehicles.
## Features
- __Vehicle Detection__: Utilizes YOLO (You Only Look Once) object detection to identify vehicles in a video stream.
- __Vehicle Tracking__: Employs the SORT (Simple Online and Realtime Tracking) algorithm to track vehicles across consecutive frames.
- __License Plate Detection__: Uses YOLO for license plate detection within the detected vehicles.
- __License Plate Recognition__: Applies OCR using the EasyOCR library to recognize characters on the license plates.
- __License Plate Format Validation__: Validates the format of recognized license plate numbers.
- __Interpolation of Missing Data__: Interpolates missing bounding box data for vehicles and license plates.
- __Visualization__: Generates a video output with annotated bounding boxes and recognized license plate numbers.
