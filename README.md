# Image Segmentation, Identification, and Analysis 

## Overview

This project implements a deep learning pipeline that processes an input image to:
1. **Segment** the objects within the image.
2. **Identify** the segmented objects using a transformer-based model.
3. **Analyze** each object to calculate attributes such as area and bounding box dimensions.
4. **Generate a summary table** containing the mapped data for each object.

The pipeline is built using `PyTorch`, `torchvision`, and `transformers` from Hugging Face.

## Features

- **Object Detection and Segmentation**: Uses a pre-trained Mask R-CNN model.
- **Object Classification**: Utilizes a transformer-based classifier for object identification.
- **Object Analysis**: Calculates the area of each object and extracts bounding box information.
- **Summary Table Generation**: Outputs a summary table with object data in CSV format.

## Dependencies

To run this project, you need the following Python libraries:

- `torch`
- `torchvision`
- `transformers`
- `pandas`
- `uuid`
- `os`
- `PIL`
- `opencv`
  
You can install the required packages using `pip`:

```bash
pip install torch torchvision transformers pandas pillow

## Usage
