# License-Plate-Detection-and-Recognition-System
This project is a Python-based system for detecting and recognizing license plates in a video stream.

It utilizes object detection and tracking techniques along with optical character recognition (OCR) to

identify license plate numbers from moving vehicles.
## Features
- __Vehicle Detection__: Utilizes YOLO (You Only Look Once) object detection to identify vehicles in a video stream.
- __Vehicle Tracking__: Employs the SORT (Simple Online and Realtime Tracking) algorithm to track vehicles across consecutive frames.
- __License Plate Detection__: Uses YOLO for license plate detection within the detected vehicles.
- __License Plate Recognition__: Applies OCR using the EasyOCR library to recognize characters on the license plates.
- __License Plate Format Validation__: Validates the format of recognized license plate numbers.
- __Interpolation of Missing Data__: Interpolates missing bounding box data for vehicles and license plates.
- __Visualization__: Generates a video output with annotated bounding boxes and recognized license plate numbers.

## Installation
1. Clone the repository: git clone https://github.com/username/repository.git

2. Install the required dependencies

3. Download the YOLOv8n model weights and place them in the specified directories.

4. Ensure that the path to the input video is correctly specified in the main.py file.

5. Use a 'file.mp4' of your own to run the program (this program is built to indentify the british licence plate format "{char}{char}{int}{int} {char}{char}{char}" 

## Usage
Run the main.py script to process the input video and generate the output. The results will be saved in a CSV file, which can be further processed or analyzed.

To interpolate missing data in the results CSV file, run the add_missing.py .

To visualize the results and generate an annotated video, run the visualize.py .

## Result
![image](https://github.com/GilShtein/License-Plate-Detection-and-Recognition-System/assets/110115156/ccd3225f-7b93-4c32-9025-178a3014afff)


