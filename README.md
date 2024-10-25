# Object Detection and Tracking with CMU Dataset and SAM2 Model

## Project Overview
This project focuses on object detection and tracking using the **CMU 3D dataset** and **Segment Anything Model 2 (SAM2)**. It extracts objects from dataset images and performs object tracking across different frames by leveraging **bounding boxes and masks**.

---

## Dataset Information
- **CMU 3D Dataset**: Contains multiple 2D images of objects (like cans, cartons, beverages) along with **mask files** for segmentation.
  
### Dataset Structure
Each folder in the dataset contains:
- **Images**: JPG files representing objects such as cans and cartons.
- **Masks**: PNG files with segmentations for the objects in the images.

---

## Installation Requirements
Install the necessary dependencies with the following commands:

```bash
pip install torch torchvision matplotlib numpy pillow
pip install sam-transformers  # Required for SAM2 model
```



## Contributors
Aditi Agrawal
Date: October 2024


## References
1. CMU dataset - https://www.kaggle.com/datasets/aditiagrawal11/cmu-dataset-images
2. SAM Model - https://www.kaggle.com/models/metaresearch/segment-anything-2/PyTorch/sam2-hiera-base-plus/1


