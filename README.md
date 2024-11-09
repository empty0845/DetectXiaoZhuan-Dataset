# DetectXiaoZhuan-Dataset

The **DetectXiaoZhuan-Dataset** is designed for training and evaluating the **detect_xiaozhuan** model with the **YOLOv5** object detection framework. This dataset simulates the task of recognizing **small seal script (小篆)** inscriptions, commonly found in **stone inscriptions**. The images are generated with a black background and white characters to simulate the effect of a **rubbing (拓片)** of seal script.
The dataset includes **30 unique characters** from the small seal script, making it suitable for text recognition and classification tasks in ancient Chinese inscriptions.

## Dataset Overview

- **Training Set**: 351 images
- **Test Set**: 75 images
- **Validation Set**: 75 images
- **Total Categories**: 30 unique characters (classes)

## Dataset Structure

The dataset is organized into the following folders:

- `images/train/` — Contains the images for training.
- `images/test/` — Contains the images for testing.
- `images/val/` — Contains the images for validation.
- `labels/train/` — Contains the annotations for training.
- `labels/test/` — Contains the annotations for testing.
- `labels/val/` — Contains the annotations for validation.

Each image is accompanied by a corresponding annotation file in YOLO format (one `.txt` file per image).

## Dataset Generation and Labeling

- **Font Used**: The dataset uses the font *全字庫說文解字.ttf*.
- **Generation Method**: The images in the dataset were generated using the Python `wordcloud` package, with the *全字庫說文解字.ttf* font to simulate the look of stone rubbings.
- **Labeling Tool**: The annotations were manually created using the *labelImg* tool, a graphical image annotation tool for object detection.

## YOLOv5 Usage

This dataset can be directly used with YOLOv5 for training, validation, and testing. Make sure to adjust the dataset configuration file to point to the correct paths for the images and annotations.

## License

This dataset is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). You are free to:

- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

Under the condition that you provide appropriate credit, indicate if changes were made, and provide a link to the license. 

Full license: [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)

## Contributors

This dataset was contributed by the following contributors:

- [empty0845](https://github.com/empty0845)
- [SparseMatric-1](https://github.com/SparseMatric-1)
- [Xi2aoyu24](https://github.com/Xi2aoyu24)
- [Eloisseee](https://github.com/Eloisseee)
