#  Triple- and Quadruple-junctions Detection using YOLOv5

This repository contains code for detecting triple- and quadruple-junctions in polycrystalline materials using the YOLOv5 object detection framework.

## Introduction

- In two-dimensional polycrystalline microstructures, triple- and quadruple-junctions are points where three grain boundaries intersect in a polycrystalline material. Detecting and analyzing these junctions aide in understanding the evolutoin of microstructures, which in turn influences the properties of materials.

- This project utilizes the YOLOv5 deep learning architecture to automatically detect tri-junctions in microstructure images. YOLOv5 is a state-of-the-art object detection model known for its accuracy and efficiency, making it suitable for real-time applications.

## Getting Started

### Prerequisites

Before running the code, ensure you have the following dependencies installed:

- Python 3.x
- PyTorch
- OpenCV
- NumPy

## Customization
- You can fine-tune the YOLOv5 model on your own dataset for better tri-junction detection performance. Refer to the YOLOv5 documentation for training instructions.

- Adjust detection parameters such as confidence threshold and NMS (non-maximum suppression) threshold in the detect.py script to suit your specific needs.

## Acknowledgements

- YOLOv5 implementation is based on the [official YOLOv5 repository](https://github.com/ultralytics/yolov5).

