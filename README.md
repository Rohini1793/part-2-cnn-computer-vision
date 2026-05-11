# Task 1: Problem Identification

## Selected Problem Type:
Image Classification

### Explanation:
This dataset contains images of manufacturing product surfaces categorized into four classes:
- normal
- scratch
- dent
- stain

Each image is assigned a single label representing the type of defect present on the product surface. The objective is to train a CNN model that can classify an input image into one of these predefined categories.

This is an image classification problem because the model predicts one class label for the entire image rather than detecting object locations or performing pixel-level segmentation.

### Why Other Problem Types Are Not Suitable:
- Object Detection: The dataset does not contain bounding boxes to locate defects.
- Semantic Segmentation: The dataset does not contain pixel-wise masks.
- Instance Segmentation: The dataset does not contain separate instance masks for defects.

### Conclusion:
Therefore, the dataset represents an Image Classification problem.