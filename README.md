# Archi Xiaozhuan Dataset

This dataset is intended for training and evaluating the **archi_xiaozhuan** model with the **YOLOv5** object detection framework.

## Dataset Overview

- **Training Set**: 351 images
- **Test Set**: 75 images
- **Validation Set**: 75 images

## Dataset Structure

The dataset is organized into the following folders:

- `images/train/` — Contains the images for training.
- `images/test/` — Contains the images and annotations for testing.
- `images/val/` — Contains the images and annotations for validation.
- `labels/train/` - Contains the annotations for training.
- `labels/test/` — Contains the annotations for testing.
- `labels/val/` — Contains the annotations for validation.

Each image is accompanied by a corresponding annotation file in YOLO format (one `.txt` file per image).

## YOLOv5 Usage

This dataset can be directly used with YOLOv5 for training, validation, and testing. Make sure to adjust the dataset configuration file to point to the correct paths for the images and annotations.

## License

This dataset is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). You are free to:

- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

Under the condition that you provide appropriate credit, indicate if changes were made, and provide a link to the license. 

Full license: [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)
