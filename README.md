## OBJECT DETECTION IN YOLO V4:


This repository provides an implementation of YOLO V4 algorithm for detecting object in image using the Darknet framework.





















































































## Architecture:

![App Screenshot](https://miro.medium.com/v2/resize:fit:1400/1*MB2XKSNOZGOHVcV2oei-8Q.png)


YOLOv4's architecture is composed of CSPDarknet53 as a backbone, spatial pyramid pooling additional module, PANet path-aggregation neck and YOLOv3 head. CSPDarknet53 is a novel backbone that can enhance the learning capability of CNN.





![App Screenshot](https://preview.redd.it/udgjuocxen651.jpg?width=1536&format=pjpg&auto=webp&s=28eef4e10e247522d5caeea2b8888c5651c93f23)

## Requirements:
*   Darknet Framework
*   Matplotlib
*   Open cv
*   Pre-trained YOLOv4 weights
*   Numpy


## Setup:
Install the dependencies: pip install opencv-python numpy

Download the YOLOv4 weights file: yolov4.weights

Download the YOLOv4 configuration file: yolov4.cfg

Download the COCO dataset labels file: coco.names
## Test Image:
![test_image](https://github.com/vishwateja19/Object-detection-using-Yolo-v4/assets/114558376/263241ce-269f-4135-9b1a-d3bd4b957b17)


## Result Image after implementation of yolo v4:
![result image](https://github.com/vishwateja19/Object-detection-using-Yolo-v4/assets/114558376/1c1192a9-5edb-409b-8afe-7c20de5b4b73)

## Acknowledgements:

 
This implementation is based on the YOLOv4 implementation . The COCO dataset is provided by Microsoft COCO.
