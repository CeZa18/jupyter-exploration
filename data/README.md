# Dataset Information

## Easy Pantry Dataset

The Easy Pantry dataset is a custom image dataset created for the ITAI 1378 Computer Vision final project. The purpose of the dataset is to train a YOLO11 object detection model to recognize common pantry items.

### Data Source

The images were collected by the project author using a mobile phone camera. Photographs were taken in pantry and refrigerator environments to capture realistic household food storage conditions.

### Target Classes

The dataset contains three custom object classes:

- pasta_box
- snack_bag
- soda_can

### Image Collection

Images include:

- Individual food items
- Multiple items in a single image
- Different object positions and orientations
- Various lighting conditions
- Pantry shelves and refrigerator storage areas

### Data Labeling

Images will be uploaded to Roboflow and manually annotated with bounding boxes for the three target classes. The labeled dataset will then be exported for YOLO11 training.

### Dataset Split

The dataset will be divided into:

- Training set
- Validation set
- Test set

The split will be generated through Roboflow during the dataset preparation process.

### Purpose

This dataset is designed to train and evaluate a custom object detection model capable of identifying pantry items and supporting an automated pantry inventory system called Easy Pantry.

### Notes

This dataset was created specifically for academic use in ITAI 1378. No personally identifiable information is intentionally included in the images. Any images containing sensitive information will be removed before training.
